# Modul-300
UeliMueli
Database with Web-Server
## Outline
1. [Description]
2. [Configuration]
3. [Test]
4. [Documentation]

## Description
Required programs:
* Installing vagrant
* Openvpn
* Networking
* Setup external server with internet access and domain name
* Configure vagrant server

### How to install vagrant
Downloading and installing vagrant from:
https://www.vagrantup.com/downloads.html

GIT is needed for vagrant:
https://git-scm.com/download/win

### How to install and connect to a Server with Openvpn
Install ``openvpn`` package:
```bash
sudo apt-get install openvpn
```
Connect to ``openvpn`` server:
```bash
sudo openvpn --config /path/to/config.ovpn
```
Source: https://askubuntu.com/questions/460871/how-to-setup-openvpn-client