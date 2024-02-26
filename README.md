# automatic_updates_linux

This code will help you to update your Linux system automaticaly

At first you need to download this code.
```
sudo apt install git
git clone https://github.com/SargsyanGrigor/automatic_updates_linux.git
cd automatic_updates_linux
```
write path/to/your/log file

open crontab
```
crontab -e
```
make your schedule
eg. 0 10 * * * /bin/bash /home/kali/automatic_updates_linux/auto.sh

After the update result will apear in log file.

# Author: Grigor Sargsyan
