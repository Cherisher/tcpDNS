How to use this python script ?
===============================


1. change your dns server to 127.0.0.1
  $ vi /etc/resolve.conf  
nameserver 127.0.0.1

2. restart the network
  $ sudo /etc/init.d/networking restart

3. run the script
  $ sudo python tcpdns.py
