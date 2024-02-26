# automatic_updates_linux

This code will help you to update your Linux system automaticaly

At first you need to download this code.
```
sudo apt install git
git clone https://github.com/SargsyanGrigor/automatic_updates_linux.git
cd automatic_updates_linux
```
# <p style="font-size: 40px; letter-spacing: 2px; color: orange;" align="center">Now I will write how I created it</p>

```
mkdir automatic_updates_linux
touch auto.sh
nano auto.sh
```

![image](https://github.com/SargsyanGrigor/automatic_updates_linux/assets/106109042/6817b944-327a-4eda-9a1d-84691f5f2743)

```
sudo su
cd /var/log
touch auto_update.log
```


```
crontab -e
```
![image](https://github.com/SargsyanGrigor/automatic_updates_linux/assets/106109042/5a15b781-e860-4705-bd22-e4775be3fe58)


make your schedule
eg. 0 10 * * * /bin/bash /home/kali/automatic_updates_linux/auto.sh

After the update result will apear in log file.

# Author: Grigor Sargsyan
