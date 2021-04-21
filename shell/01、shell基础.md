# shell基础

#### shell是什么
* shell是一个命令行解释器，它为用户提供了一个向Linux内核发送请求以便运行程序的界面系统级程序，用户可以用shell启动、挂起、停止甚至编写一些程序
* shell还是一个功能相当强大的编程语言、易编写、易调用、灵活性较强。shell是解释执行的脚步语言，在shell中可以直接调用Linux系统命令

#### shell分类
shell主要两种语法类型有Bourne和C，这两种语法彼此不兼容。  
Bourne家族主要包括sh、ksh、Bash、psh、zsh；  
C家族主要包括：csh、tcsh
```
查看当前系统支持哪些shell
cat /etc/shells

当前系统执行的shell
echo $SHELL
```