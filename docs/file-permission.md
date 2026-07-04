# Linux File Permissions

## Objectives

- Ownership
- Groups
- chmod
- chown
- chgrp
- umask
- SetUID
- SetGID
- Sticky Bit

## Commands Used

sudo chown devuser:devteam /projectdata

sudo chmod 770 /projectdata

chmod 755 report.txt

chmod 644 backup.txt

chmod u+x report.txt

chmod g+w report.txt

chmod o-r report.txt

umask 027

chmod 4755 /usr/local/bin/demoapp

chmod 2775 /projectdata

chmod +t /shared

## Verification

ls -l

ls -ld
