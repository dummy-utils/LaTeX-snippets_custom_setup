# LaTeX UltiSnips + VimTeX Configuration - Ubuntu 22.04.1

## Requirements

The configuration of UltiSnips & VimTeX requires the following things: git, vim, python3, python3-pip, perl, latexmk and a generix TeX distribution.

### Git Setup

You can use the command 

```
~$ git --version
```

to check which version of git is installed in your sistem. If your system does not include git by default,  you can download it directly from your terminal

```
~$ sudo apt install git
```

### Vim & GVim Setup

If your system does not include Vim & GVim by default, you can use 

```
~$ sudo apt install vim-gtk3
```

to install both Vim & GVim on your system.

To get the best experience, you should learn about Vim plugins and how to manage them. 

First of all, you need to create a folder named `.vim` in your home directory, meaning that you need to create a folder inside the `~` directory. This can be done using 

```
~$ mkdir .vim
```

Now you can create the autoload directory that we'll be using to handle the plugin manager.

```
~$ cd .vim                   % to enter .vim folder
~/.vim$ mkdir autoload       % to create autoload folder
```


### Python3 / Python3-pip Setup

Ubuntu should have python3 by default, and in most cases you'll need to install only pip. You can do that with the following command.

```
~$ sudo apt install python3-pip
```

Anyway, if you do not have python 3 you can install it using this command.

```
~$ sudo apt install python3
```

### Perl Setup

You should have perl installed by default on Ubuntu. If this is not the case, you can use the following command to install it.

```
~$ sudo apt install perl
```

### Texlive distribution Setup

You can choose a distribution of your choice to install on your system. Anyway, if you want something standard, you can install a base bundle of texlive using the following command.

```
~$ sudo apt install texlive-base
``` 

### latexmk Setup

latekmk is useful to compile a `.tex` document the right amount of times in order to synchronize references & citations, as well as other things. You can get latekmk using 

```
~$ sudo apt install latekmk
``` 



