source : [here](https://youtu.be/Y-pd5iTXJjs?si=6weiVa_3n2e3BCvE)

## How to check current default permission?

```umask``` or ```umask -S```
output: octal format ```0022``` or ```0002```  

- permission will be
```0777``` - ```0022``` = ```0755```  

example = ```umask u+rw, g+rw,o-r```  

## To change Default permission permanently

Add the permission in ```.bashrc``` file  






