#root ubuntu via ssh

#change config
1. sudo nano cd /etc/ssh/sshd_config
2. change premitrootlogin to yes (remove #)
3. change root passwd : sudo passwd
4. systemctl restart ssh



# update.sh
This simple update and upgrade file Linux ubuntu

1. cd /usr/local/bin

2. wget https://raw.githubusercontent.com/hadiportofolio/update.sh/main/update.sh

3. sudo chmod +x /usr/local/bin/update.sh

4. ./update.sh


