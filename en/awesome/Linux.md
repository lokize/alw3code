---
title: "Linux"
token: "Linux"
category: linux
description: "CheatSheets for Linux Users"
media: https://github.com/lokize/alw3code/blob/main/img/linux.png?raw=true
git: https://github.com/lokize/alw3code/blob/main/img/linux.jpg?raw=true
by: "Lokize"
---

## View linux version

```
cat /etc/os-release
lsb_release -a
hostnamectl
uname -r
```

## Setar Hostname CentOS

```
hostnamectl set-hostname meuservidor.meudominio.br
```

## Install wget

```
sudo yum install wget
```

## Install unzip

```
yum install unzip
```

## Install nano

```
sudo yum install -y nano
```

## Fix Tomcat Manager Acess

```
<Context antiResourceLocking="false" privileged="true" > <Valve className="org.apache.catalina.valves.RemoteAddrValve" allow="127\.\d+\.\d+\.\d+|::1|0:0:0:0:0:0:0:1" /> </Context>
```

## Install locate

```
sudo yum install mlocate [On CentOS/RHEL]
sudo apt install mlocate [On Debian/Ubuntu]
```

### update db locate

```
sudo updatedb
```

## Show Hidden Files in Terminal

```
ls -ld .?*
```

## Clear terminal history

```
history -c
```

## See History Terminal

```
history
```

## View Open Ports

```
sudo netstat -tulpn
```

## Check the Status of Firewalld

```
systemctl status firewalld
```

## Enable Firewalld

```
systemctl enable firewalld
```

## Start Firewalld

```
systemctl start firewalld
```

## List Firewalld Services

```
sudo firewall-cmd --list-services
```

## List Firewalld Ports

```
sudo firewall-cmd --list-ports
```

## Check Firewall

```
sudo firewall-cmd --state
```

## Stop Firewall

```
sudo systemctl stop firewalld
```

## Disable Firewall

```
sudo systemctl disable firewalld
```

## Searching history

You can also use history to rerun the last command you entered by typing !!. By pairing it with grep, you can search for commands that match a text pattern or, by using it with tail, you can find the last few commands you executed. For example:


```
history | grep dnf
sudo dnf update -y
history | grep dnf
```

Searching with tail

```
history | tail -n 3
history
history | grep dnf
history | tail -n 3
```

## Search history

```
history | grep -i searchterm
```
