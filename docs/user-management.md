# User and Group Administration

## Users Created

- devuser1
- devuser2
- Manager
- manager1

## Groups Created

- devteam
- managers

## Commands Used

sudo adduser devuser1
sudo useradd devuser2
sudo useradd Manager
sudo useradd manager1
sudo adduser manager1
sudo groupadd devteam
sudo groupadd managers
sudo usermod -aG devteam devuser
sudo gpasswd -d groupname username
sudo passwd -x 30 devuser
sudo visudo
sudo su - devuser1

## Verification

groups devuser1
id devuser1
chage -l devuser1
