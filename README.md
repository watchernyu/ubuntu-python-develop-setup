# ubuntu-python-develop-setup
A short guide on setting up python development environments on Ubuntu, mainly for my own reference. I decided that whenever I encountered a problem I will try fix it and post the solution here. 

## make Ubuntu ready for development, make sure you install the drivers correctly
Especially graphics drivers, if not correctly installed, can lead to a whole bunch of problems:

reference: https://linuxconfig.org/how-to-install-the-nvidia-drivers-on-ubuntu-18-04-bionic-beaver-linux
```
ubuntu-drivers devices
sudo ubuntu-drivers autoinstall
```

## install Anaconda3, download .sh file, chmod +x, run
https://www.anaconda.com/download/#linux

## install Pycharm 
## install Filezella

## Latex-related
Install texlive-science: https://linuxconfig.org/how-to-install-latex-on-ubuntu-18-04-bionic-beaver-linux (`sudo apt install texlive-science`)

font missing `bbm`, see https://tex.stackexchange.com/questions/203184/installing-bbm-sty-in-linux for highest vote answer (`sudo apt-get install texlive-fonts-extra`). 



## ubuntu in virtual box, connection problem, see the high-vote short answer but not the accepted answer:
https://askubuntu.com/questions/419327/how-can-i-make-virtualbox-guests-share-the-hosts-vpn-connection


