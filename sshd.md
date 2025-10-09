#### Activating SSHD

> *make sure your network settings (if using corporate network(internal))
 in virtualbox is connected as a **bridged adapter** and selecting the
 necessary network card used*

> *make sure you are logged in to your linux environment as your user account
 (not root) as **sudo** is used when not in root account.*


##### install OpenSSH Server
- sudo systemctl install openssh-server

##### also, update your sshd status
- sudo systemctl update sshd

##### enable sshd to start on boot
- sudo systemctl start sshd

##### check again, to see if sshd service is active (it shoud show active: running in green )
- sudo systemctl status sshd

#### check to see the IP address
- ip addr

> *open PuTTY and insert the ip address and connect*



  
