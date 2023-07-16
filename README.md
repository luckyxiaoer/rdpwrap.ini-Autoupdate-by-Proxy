# rdpwrap.ini Autoupdate using proxy
forked from [asmtron/rdpwrap](https://github.com/asmtron/rdpwrap/tree/master)

Autoupdate rdpwrap.ini file behind a proxy

If you are in the location must use a proxy to visit Github, this autoupdate.bat file is suitable for you

following the instructions on [Download and Install](https://github.com/asmtron/rdpwrap/blob/master/binary-download.md)

after finishing all of that, change the autoupate.bat in “C:\Program Files\RDP Wrapper” folder autoupdate.bat  file in this repo.

and run with administration, you will get it auto-updated 

# modify the proxy configuration 
you need to modify the configuration to make it fit for your proxy

in line：348

```
        Dim proxyServer, proxyPort
        proxyServer = "127.0.0.1"
        proxyPort = 7890
```
