# known-hosts
SSH known hosts

e.g. 
````
known-hosts delete 23
known-hosts scan www.microsoft.com
known-hosts help
````

Provides:

 r remove server's key
 a scan = scan for the server's key
 t tail = look at the last few lines of the known hosts file
 d delete N = delete line number N from hosts file
 undo = restore backup file (prototype)
