#### Install `.deb` paths:
```c#
sudo dpkg -i pacote.deb
```
#### Uninstall:
```c#
sudo apt-get remove nomedopacote
```

#### Error:
You might want to run 'apt --fix-broken install' to correct these.
#### Code to fix:
```c#
 sudo apt-get install --fix-broken
 ```



