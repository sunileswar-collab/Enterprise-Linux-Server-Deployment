# Service & Process Management

## Objectives

- Package installation
- Service management
- Process management
- Logs
- Startup services

## Installed Packages

apache2
nginx
openssh-server
htop
curl
wget
vim

## Commands Used

sudo apt update

sudo apt install apache2 nginx

systemctl start apache2

systemctl enable apache2

systemctl status apache2

systemctl status ssh

ps aux

htop

journalctl -u apache2

journalctl -xe

ss -tulpn
