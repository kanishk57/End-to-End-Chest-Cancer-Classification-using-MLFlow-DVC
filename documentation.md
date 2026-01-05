what broke, why broke, how it was fixed. 

1,
a,  ![alt text](image-1.png)
    could not download TF with/without a specified version.
b,  there was multiple layers of errors, checked proxy, configs, firewall protection, tried upgrading pip, reinstalling python, changed multiple venvs. 
c, eventually when nothing worked i installed all dependencies using Ubuntu WSL because it bypass all the proxy configurations. ![alt text](image-2.png)



2, 
a, was having problem with executing data ingestion pipeline
b, i had types Config/Config.yaml instead of using lower cases.
c, debug through the files, made changes, saved, restarted kernal and ran it again
