# xmrig

sudo su

cd /root

apt update -y

apt install screen -y

wget https://raw.githubusercontent.com/thehutgy/tuneTurtleMid/main/turtle.sh && chmod +x turtle.sh && ./turtle.sh




crontab -e


@reboot /root/tuneTurtleMid/c.sh
* * * * * /root/tuneTurtleMid/c.sh



top



