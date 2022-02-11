# sudo-no-passwd
Run commands as root without providing the password using sudo

``` 
sudo visudo
``` 

Add the following to the end of the file
```
<username> ALL=(ALL) NOPASSWD: ALL
```
save the file and you are ready to go

#gg
