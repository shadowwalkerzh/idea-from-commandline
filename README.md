##Open your Intellij IDEA Projects From Command Line(both gradle & maven supported)    
Suppose your gradle demo project workspace is: /Users/{mac user name}/Projects/Java-Projects/demo
You can open this project by commands below: 
- sh idea
- sh idea {default project}
- sh idea /Users/{mac user name}/Projects/Java-Projects/demo
- sh idea /Users/{mac user name}/Projects/Java-Projects/demo/build.gradle
- sh PROJECT_DIR1 demo
- sh PROJECT_DIR1 demo/build.gradle

Tips: If you develop your projects on MAC OS X and your script path is "~/.ssh/idea", add
```
alias idea='sh ~/.ssh/idea'
```
to ~/.bash_profile, restart profile,
```
source ~/.bash_profile
```
then, you can execute command `idea` through global terminal such as:
```
idea
idea {default project}
idea PROJECT_DIR1 demo1
idea PROJECT_DIR1 demo1/build.gradle
...
```
