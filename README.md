# 🛸 &nbsp; Ubuntu startup guide 🛸
 
---
## ✔ &nbsp; Aptitude   
- What is aptitude command Ubuntu? [click here](http://manpages.ubuntu.com/manpages/bionic/man8/aptitude-curses.8.html#description) ☄️

- Open Terminal (CTRL + ALT + T) 

`Type the command:`

    $ sudo apt-get install aptitude -y

## ✔ &nbsp; Update

- Open Terminal (CTRL + ALT + T) 

`Type the command:`

    $ sudo apt-get update -y

## ✔ &nbsp; Upgrade

- Open Terminal (CTRL + ALT + T) 

`Type the command:`

    $ sudo apt-get upgrade -y


## ✔ &nbsp; Rar Unrar

- Open Terminal (CTRL + ALT + T) 

`Type the command:`

    $ sudo apt-get install rar unrar -y

##  ✔ &nbsp; Google Chrome
- Download: [click here](https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb) ☄️ 

---
# ☠&nbsp; 💻 &nbsp;☕ &nbsp; ESSENTIALS FOR PROGRAMMERS ☕&nbsp; 💻 &nbsp;☠

## ✔ &nbsp; JAVA 8 - 14
- Open Terminal (CTRL + ALT + T) 

`Type the command:`

    $ sudo add-apt-repository ppa:linuxuprising/java && sudo apt update && sudo apt install openjdk-8-jdk oracle-java14-installer -yV
    
## ✔ &nbsp; Docker 🐋
- Open Terminal (CTRL + ALT + T) 

`Type the command:`

    $ sudo apt-get install wget curl && sudo curl http://get.docker.com |sh -y
    $ sudo usermod -aG docker username
    $ sudo curl -L "https://github.com/docker/compose/releases/download/1.26.0/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
    $ sudo chmod +x /usr/local/bin/docker-compose
    $ docker-composer -version 


