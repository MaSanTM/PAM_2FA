# ISO200-PAM 
##A PAM 2FA project to the ISO200 class at FATEC Americana.


For use, you'll need an **Arch Linux** distribution: https://archlinux.org/download/

The version, is very irrelevant.

# /bin/bash

The file userLogin.c was created to insert him inside the _/bin/bash_ directory on distribution. As we know, this directory contains all binaries of the system, ie we can run the command direct from the Shell. For example:
```
~$ userLogin
~$ A Token was sent to your device, insert in to proceed:
~$
```
And will activate the determinate command for the Two Factor Authentication. You can the _.c_ file into the directory simple following the script:
```bash
echo userLogin.c >>> /bin/bash
```
Then you can test running the "new command".
