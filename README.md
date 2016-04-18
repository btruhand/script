**Kibana Init**

Init file for kibana program located under /usr/local/kibana4. Made for CentOS  

Steps to start:
```
sudo su
cd /etc/init.d
wget https://raw.githubusercontent.com/btruhand/script/master/kibana --no-check-certificate
chkconfig --add kibana
chkconfig kibana on

# checkpoin, level 2,3,4,5 on
chkconfig --list

chmod +x kibana
service kibana start
```

To stop:
```
service kibana stop
```
