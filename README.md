## How to check current default persmission?

```umask``` or ```umask -S```
output: octal format ```0022``` or ```0002```  

- permission will be
```0777``` - ```0022``` = ```0755```  

example = ```umask u+rw, g+rw,o-r```  

## To change Default permission permanently

Add the permission in ```.bashrc``` file  






