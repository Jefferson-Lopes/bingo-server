# BINGO server

BINGO telescope server, with Node-RED dashboard host, MySQL database, containerized Ubuntu machines and Jupyter notebook server

## Docker create command

### LXDE desktop environment

```
docker run -d --name xxxxx -p xxxx:80 -e USER=xxxxx -e PASSWORD=xxxxx -e VNC_PASSWORD=xxxxx dorowu/ubuntu-desktop-lxde-vnc:focal
```

### LXQt desktop environment

```
docker run -d --name xxxxx -p xxxx:80 -e USER=xxxxx -e PASSWORD=xxxxx -e VNC_PASSWORD=xxxxx dorowu/ubuntu-desktop-lxde-vnc:focal-lxqt
```


## Reference

* [Ubuntu SSH server problem](https://askubuntu.com/questions/1161579/ssh-server-cannot-be-found-even-though-installed)
* [Ubuntu Firewall](https://creodias.eu/-/how-to-open-ports-in-linux-)
* [Install docker engine](https://docs.docker.com/engine/install/ubuntu/)
* [Docker ubuntu VNC](https://github.com/fcwu/docker-ubuntu-vnc-desktop)
* [Docker resize issue](https://github.com/fcwu/docker-ubuntu-vnc-desktop/issues/115#issuecomment-522426037)

