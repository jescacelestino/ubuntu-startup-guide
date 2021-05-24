# 💡 &nbsp; Ubuntu startup guide 💡
 
---
## ⚡ &nbsp; Aptitude   
- What is aptitude command Ubuntu? [click here](http://manpages.ubuntu.com/manpages/bionic/man8/aptitude-curses.8.html#description)

- Open Terminal (CTRL + ALT + T) 

`Type the command:`

    $ sudo apt-get install aptitude -y
    
## ⚡ &nbsp; Wine 🍷

- Open Terminal (CTRL + ALT + T) 

`Type the command:` 
    
    $ sudo apt-get install wine -y

## ⚡ &nbsp; Update && Upgrade

- Open Terminal (CTRL + ALT + T) 

`Type the command:`

    $  sudo apt-get update && sudo apt-get upgrade -y


## ⚡ &nbsp; Rar Unrar 7zip

- Open Terminal (CTRL + ALT + T) 

`Type the command:`

    $ sudo apt-get install rar unrar p7zip-full -y
    
## ⚡ &nbsp; Geany

- Open Terminal (CTRL + ALT + T) 

`Type the command:`

    $ sudo apt-get install geany -y    
    
## Configurar a tecla "PrtSc" para usar o flameshot
https://askubuntu.com/questions/1036473/how-to-change-screenshot-application-to-flameshot-on-ubuntu-18-04

## Install Python 2.7
https://tecadmin.net/install-python-2-7-on-ubuntu-and-linuxmint/

## Install oh my zsh
https://blog.rocketseat.com.br/terminal-com-oh-my-zsh-spaceship-dracula-e-mais/
---
# 🚀 &nbsp; ESSENTIALS FOR PROGRAMMERS 🚀

## JAVA 8 - 15 ☕ 
- Open Terminal (CTRL + ALT + T) 

`Type the command:`

    $ sudo add-apt-repository ppa:linuxuprising/java && sudo apt-get update && sudo apt-get install openjdk-8-jdk && sudo apt-get install openjdk-11-jdk && sudo apt-get install oracle-java15-installer -y
    
## Docker 🐋
- Open Terminal (CTRL + ALT + T) 

`Type the command:`


    $ sudo apt-get install curl 
    $ curl https://get.docker.com | sh
    $ sudo usermod -aG docker username (após reiniciar ele funciona)
    $ docker run hello-world
    $ sudo curl -L "https://github.com/docker/compose/releases/download/1.26.0/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
    $ sudo chmod +x /usr/local/bin/docker-compose
    $ docker-compose -version 
    $ sudo curl -L https://raw.githubusercontent.com/docker/compose/1.26.0/contrib/completion/bash/docker-compose -o /etc/bash_completion.d/docker-compose
    $ sudo curl -L https://raw.githubusercontent.com/docker/machine/v0.16.0/contrib/completion/bash/docker-machine.bash -o /etc/bash_completion.d/docker-machine


## SSH - KEY tutorial
- [click here](https://medium.com/@rgdev/como-adicionar-uma-chave-ssh-na-sua-conta-do-github-linux-e0f19bbc4265)
---
Made with ❤️ &nbsp; by [Jéssica](https://www.instagram.com/jescacelestino/) ☄️
