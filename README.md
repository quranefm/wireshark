# CSN-150
Wireshark application
<img 
![images](https://user-images.githubusercontent.com/90719446/143929040-84be5f97-012e-49ab-bdf1-1d2a52fa2568.jpeg)

Wireshark is a free open source software that you can use to analyze packets, Wireshark is a very handy and useful tool in networking, it helps researchers do data analysis
when it comes to networking traffic and it can used be used by hackers for security purposes. 

Virtual Machine (VirtualBox):
Search for VirtualBox on any brower and the first which will appear will be from VirtualBox OSE so, click on the link and once this link opens you just need to click on the downloads tab to download and after downloading you just need to install. VirtualBox is a free tool which will enable you to rub different operating systems virtually on your host operating system.

Installing Ubuntu (20.04) on VirtualBox:
Downloading the ISO file for Ubuntu on VirtualBox. For downloading the ISO file of Ubuntu, you just have to search for Ubuntu and first link which will appear here will be from ubuntu.com just click on the first link and right away you will see this option here it says what's new in Ubuntu 20.0 for because 20.04 is the latest version or the recent release. Look for the downloads tab and when click on the download tab you will see the Ubuntu desktop so you can click on the version which is available, and you should install the "LTS" version when click download. 
Once you have downloaded the ISO file install ubuntu on VirtualBox. Click on the new button and once you click on the new button you can provide the name of your new machine. Once giving it a name straightway VirtualBox is smart enough to provide default setting. Now head to the storage section when you need to provide the location of the ISO file that was downloaded, so click on the empty option under the controller choose the CD icon option the click on "choose a disk file" than browse to the location where the download is. 
Now you can start the Ubuntu installation, after starting up the ubuntu installation is going to start, select the language, keyboard layout and location.

Installing Wireshark: First thing is to open the terminal then type the command "ip addr" to show you your Ip address. Type "sudo apt update" to update the refernce, sudo allows you to run the root privileges it going to ask you for your password. After updating type "sudo apt install wireshark" to install wireshark the type yes to install the software. In my opinion this is the easy way to install wireshark some people like to go on the wireshark site and download it from there. When configuring wireshark-common you want to leave it as no, no is set as default. After wireshark you want to reopen terminal and type "sudo wireshark" now you can start capturing packets.

<img width="1280" alt="Screen Shot 2021-11-29 at 1 51 35 PM" src="https://user-images.githubusercontent.com/90719446/143927700-7cbb8d3a-b806-49af-a281-5860725beebe.png">

<img width="1280" alt="Screen Shot 2021-11-29 at 1 52 45 PM" src="https://user-images.githubusercontent.com/90719446/143928074-a973ef27-f661-49f8-b7e5-5117a2da5d5f.png">


<img width="1280" alt="Screen Shot 2021-11-29 at 1 53 10 PM" src="https://user-images.githubusercontent.com/90719446/143927904-234c8e24-8d2d-4fae-b8ae-ea1f9e4aca01.png">

<img width="1280" alt="Screen Shot 2021-11-29 at 1 54 42 PM" src="https://user-images.githubusercontent.com/90719446/143928253-558b5287-958c-465f-9088-e49ce3845170.png">


Some of the reasons people use this software is to troubleshoot network problems, examine security problems and debug protocols implementations.

Youtube:
https://youtu.be/tIsAoRtI2y0

Final Review:
Overall the software is a very hand it let you all the communication the network, so if you connected to a wireless access point you can see all the traffic coming from user on the network. Understanding how normal traffic look like is important so you know if something going wrong on your network, like with a DDos attack there is a specific type of format you can identify just by looking, DDos attack is a flood of the same traffic

(Pros) 
You can who on the network, you can user for troubleshooting, 
(Cons)
Some people information might be encrypted,
I would use Wireshark it easy to understand and straightforward, Ive learned that wireshark is a powerful tool to know.



References:
https://blog.wireshark.org
https://computingforgeeks.com/how-to-install-wireshark-on-ubuntu-desktop/

