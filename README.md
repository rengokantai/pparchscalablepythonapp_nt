# pparchscalablepythonapp_nt

### 8 Secure Coding and Vulnerabilities
Secure system
- a secure architecture involves creating a system that is able to provide access
to data and information to authorized people and systems while preventing any 
unauthorized access

CIA triad
- confidentially
- integrity
- availablity


### 9 Is Python Secured
this can pass the test
```
python test eval.py "__import__('os').system('ls -la')"
```

more safer:
```
eval(string,{'__builtins__':{})
```
