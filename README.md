# BINGO telescope server

BINGO telescope server, with Node-RED dashboard host, MySQL database, containerized Ubuntu machines and Jupyter notebook server

# JupyterHub server

## New account

Make a request to the HVEN admin for a new Jupyter user account

## First login

Go to your browser and enter the link below:

    http://XXX.XXX.XXX.XXX:YYYY

and log in using the new account username and password

## Changing password

For safety matters, the JupyterHub admin only creates new user with a standard password and it is up to the user to set a new one.

First thing to do is to open a new terminal window inside the jupyter by going to **File->New->Terminal**, then run the command:

    passwd

the console will ask you for the current password, the one the admin gave you, then to set and repeat the new password.

And that's it, the environment is setup and secure, ready to use!

# Docker create command

## LXDE desktop environment

    docker run -d --name xxxxx -p xxxx:80 -e USER=xxxxx -e PASSWORD=xxxxx -e VNC_PASSWORD=xxxxx dorowu/ubuntu-desktop-lxde-vnc:focal

## LXQt desktop environment

    docker run -d --name xxxxx -p xxxx:80 -e USER=xxxxx -e PASSWORD=xxxxx -e VNC_PASSWORD=xxxxx dorowu/ubuntu-desktop-lxde-vnc:focal-lxqt

# Reference

* [Ubuntu SSH server problem](https://askubuntu.com/questions/1161579/ssh-server-cannot-be-found-even-though-installed)
* [Ubuntu Firewall](https://creodias.eu/-/how-to-open-ports-in-linux-)
* [Install docker engine](https://docs.docker.com/engine/install/ubuntu/)
* [Docker ubuntu VNC](https://github.com/fcwu/docker-ubuntu-vnc-desktop)
* [Docker resize issue](https://github.com/fcwu/docker-ubuntu-vnc-desktop/issues/115#issuecomment-522426037)
* [JupyterHub docker](https://hub.docker.com/r/rancavil/jupyterhub-docker)
