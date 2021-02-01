# RedGhost
Post exploitation framework

### Installation 
```
git clone https://github.com/Ba-hub/ghostHUB

chmod +x *

sudo bash install.sh

sudo bash ghostHUB.sh 

``` 

- Payloads

Function to generate various encoded reverse shells in
netcat, bash, python, php, ruby, perl

- SudoInject

Function to inject sudo command with wrapper function to run a reverse root shell everytime "sudo" is run for privilege     escalataion

- lsInject 

Function to inject the "ls" command with a wrapper function to run payload everytime "ls" is run for persistence

- SSHKeyInject

Function to log keystrokes of a ssh process using strace

- Crontab

Function to create cron job that downloads payload from remote server and runs payload every minute for persistence

- SysTimer

Function to create systemd timer that downloads and executes payload every 30 seconds for persistence.

- GetRoot

Function to try various methods to escalate privileges


- Clearlogs

Function to clear logs and make investigation with forensics difficult


- MassInfoGrab

Function to grab mass reconaissance/information on system

- CheckVM

Function to check if the system is a virtual machine


- MemoryExec

Function to execute remote bash script in memory


- BanIp

Function to BanIp using iptables


### Requirements

```
apt install dialog 
apt install gcc 
apt install iptables 
apt install strace

```
