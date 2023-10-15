# Mac-OS-config-
MacOS configuration environment variable zsh /bash
Bash and zsh configuration in macos terminal 


to save :
# press Insert to edit and :wq and enter to save


Run command : - ```export```  To show all path environment variable



**Set this path to solve errors for zsh ,ls ,clear and etc not found s**

```export PATH=$PATH:/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin```




Last login: Tue Oct  3 10:24:23 on console

/Users/manan/.zshrc:9: no such file or directory: /manan

manan@manan ~ % ```export```

ANDROID_SDK=/Users/manan/Library/Android/sdk

HOME=/Users/manan

```JAVA_HOME=/Library/Java/JavaVirtualMachines/temurin-17.jdk/Contents/Home```

LC_CTYPE=UTF-8

LOGNAME=manan

NVM_BIN=/Users/manan/.nvm/versions/node/v18.14.0/bin

NVM_CD_FLAGS=-q

NVM_DIR=/Users/manan/.nvm

NVM_INC=/Users/manan/.nvm/versions/node/v18.14.0/include/node

OLDPWD=/Users/manan

PATH=/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin

PWD=/Users/manan

SHELL=/bin/zsh

SHLVL=1

SSH_AUTH_SOCK=/private/tmp/com.apple.launchd.WDJJW8VZp3/Listeners

TERM=xterm-256color

TERM_PROGRAM=Apple_Terminal

TERM_PROGRAM_VERSION=447

TERM_SESSION_ID=6CEB2261-94A5-4C34-8ADD-BF4FF112D029

TMPDIR=/var/folders/v1/8x46l9m91xq37tcqg56snjm40000gp/T/

USER=manan

XPC_FLAGS=0x0

XPC_SERVICE_NAME=0

__CFBundleIdentifier=com.apple.Terminal





You can check history of existing executed commands :- ```history```





 ```echo $JAVA_HOME```    Command to display specific path



Command to set java jdk path or change installed java path

```export JAVA_HOME=/Library/Java/JavaVirtualMachines/temurin-17.jdk/Contents/Home```





Command to add multiple environment variables  paths in single file  in zshell

```nano ~/.zshrc``` or ```vim ~/zshrc```



To change shell bash/zsh 

```chsh -s /bin/zsh``` for zsh

Or  ```chsh -s /bin/bash for bash``` 




To change or add paths in  ```zsh_profile``` or ```bash_profile``` 

Run this command



If you have installed nano you can run 

```nano ~/.zsh_profile```  



If you have installed vim editor you have to run this command

```Vim ~/.zsh_profile```   or ```Vi ~/.zsh_profile```







