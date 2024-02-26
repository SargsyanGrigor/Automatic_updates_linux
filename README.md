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


![Screenshot 2024-02-26 163950](https://github.com/SargsyanGrigor/automatic_updates_linux/assets/106109042/4d603b34-2d8a-47b3-85fd-2f5a8aedbd44)


![Screenshot 2024-02-26 164030](https://github.com/SargsyanGrigor/automatic_updates_linux/assets/106109042/4ea851fb-ddf0-42f2-86b0-6f11b5546d2e)

After the update result will apear in log file.

# Author: Grigor Sargsyan
