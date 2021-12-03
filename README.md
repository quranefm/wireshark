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
* adduser (yourname)
* usermod -aG sudo (yourname)
* ufw app list
* ufw allow OpenSSH
* ufw enable
* ufw status
* sudo apt install tasksel
* apt update && upgrade -y
* sudo tasksel
* sudo apt install xrdp
* sudo systemctl enable xrdp
* sudo systemctl start xrdp
* sudo ufw status
* sudo ufw allow 3389/tcp
* sudo ufw reload
* sudo apt install xfce4
* echo "xfce4-session"  "greater than symbol"  /home/YOURUSERNAME/.xsession



