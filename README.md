# Linux Commands for Cloud Engineers

This repository contains important Linux commands useful for cloud engineers, DevOps engineers, and system administrators.

---

## File & Directory Management

ls      # list files
pwd     # show current directory
cd      # change directory
cp      # copy files
mv      # move/rename files
rm      # delete files

---

## File Permissions

chmod   # change permissions
chown   # change file ownership

Example:
chmod 755 file.sh

---

## Disk Usage

df -h   # check disk space
du -sh  # check folder size

---

## Process Management

ps aux      # show running processes
top         # system monitor
kill -9 PID # kill process

---

## Networking Commands

ping google.com
ifconfig
netstat -tulnp

---

## System Information

uname -a     # system information
whoami       # current user
uptime       # system uptime
hostname     # system hostname

---

## Package Management (Ubuntu)

sudo apt update
sudo apt upgrade
sudo apt install package_name
sudo apt remove package_name

---

## File Search

find / -name filename
grep "word" file.txt
