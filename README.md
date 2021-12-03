# CSN-150

Wireshark Open Source Tool

# Links You Will Need:
Digital Ocean Website: https://www.digitalocean.com/

# Synopsis:
Wireshark is a free open source software that you can use to analyze packets, Wireshark is a very handy and useful tool in networking, it helps researchers do data analysis
when it comes to networking traffic and it can used be used by hackers for security purposes. 

# Applications Used:
Digital Ocean

Ubuntu 20.04

Microsoft Remote Desktop

Wireshark

# Installation:

* Go to Digital Ocean and create a account after creating the account you have to create a "Droplet"
* On Mac open Terminal to began, on PC you have to open console within Digital Ocean
* In Terminal you're going to enter "ssh root@'The Ip Address To The Droplet" ex ssh root@169.254.55.1
* The Login is root and the password is the same one you created or if you used ssh check your email
* After you're loged in follow the following commands 
* run "sudo apt update"
* adduser (yourname)
* usermod -aG sudo (yourname)
* ufw app list
* ufw allow OpenSSH
* ufw enable
* ufw status
* sudo apt install tasksel
* sudo tasksel
* sudo apt install xrdp
* sudo systemctl enable xrdp
* sudo systemctl start xrdp
* sudo ufw status
* sudo ufw allow 3389/tcp
* sudo ufw reload
* sudo apt install xfce4
* echo "xfce4-session"  "greater than symbol"  /home/YOURUSERNAME/.xsession

# Youtube: 
https://youtu.be/lqZZ_HtE4go

# Final Review:

Overall the software is a very hand it let you all the communication the network, so if you connected to a wireless access point you can see all the traffic coming from user on the network. Understanding how normal traffic look like is important so you know if something going wrong on your network, like with a DDos attack there is a specific type of format you can identify just by looking, DDos attack is a flood of the same traffic

# References:

https://blog.wireshark.org
https://computingforgeeks.com/how-to-install-wireshark-on-ubuntu-desktop/

# Problems:

Could get wireshark to open and run on the cloud 






