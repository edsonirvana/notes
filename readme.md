#### Install `.deb` paths:
```c# sudo dpkg -i pacote.deb```
#### Uninstall:
```c# sudo apt-get remove nomedopacote ```

#### Error: You might want to run 'apt --fix-broken install' to correct these.
```c#
 sudo apt-get install --fix-broken
 ```

tar -zxvf  nome do arquivo terminado em .tar.gz

tar -zxvf  nome do arquivo terminado em .tar.gz

Error: You might want to run 'apt --fix-broken install' to correct these.

ex: Err:1 http://dl.google.com/linux/earth/deb stable InRelease                    
  The following signatures couldn't be verified because the public key is not available: NO_PUBKEY 4EB27DB2A3B88B8
solve: sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 4EB27DB2A3B88B8

