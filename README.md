<h2> Description </h2>
This project gave me experience in network configuration, log generation and analysis, Splunk query and showed both attack and detect scenario of SOC operation.

<h2> Installing Operating Systems </h2>

<h3> Windows 10 Installation </h3>
Here the first thing is to install media creation tool as shown below
<img src = "image/1.png" height = 300, width = 600>
Only after the media creation tool is downloaded we can access the link to Windows 10. And then we can download the iso file of Windows 10. The first step s to accept the terms and agreements.
<img src = "image/2.png" height = 300, width = 600>
After that, choose the option Create Installation Media for another PC. Then, choose English as your language and after that, choose iso file option to download.
<img src = "image/3.png" height = 300, width = 600>
<img src = "image/4.png" height = 300, width = 600>
<img src = "image/5.png" height = 300, width = 600>
<img src = "image/6.png" height = 300, width = 600>
In oracle virtual box, create a new space for windows 10. And select the windows iso file from downloads folder as shown below:
<img src = "image/7.png" height = 300, width = 600>
Choose base memory as 4064 and number of CPUs as 1.
<img src = "image/8.png" height = 300, width = 600>
Choose English as your language. Then after click I do not have a product key option and agreed to the terms.
<img src = "image/9.png" height = 300, width = 600>
<img src = "image/10.png" height = 300, width = 600>
<img src = "image/11.png" height = 300, width = 600>
Choose Driver 0 unallocated space and start installing files.
<img src = "image/12.png" height = 300, width = 600> 
<img src = "image/13.png" height = 300, width = 600>

<h3> Windows Server Installation </h3>
For server installation, type windows 22 server download in google and it will lead you to the correct link and download the file.
For server installation, type windows 22 server download in google and it will lead you to the correct link and download the file.
<img src = "image/14.png" height = 300, width = 600>
Then, choose the file from the download and mount it in virtual space
<img src = "image/15.png" height = 300, width = 600> 
<img src = "image/16.png" height = 300, width = 600>
After that allocate base memory as 4096 and number of CPUs as 1. Choose Hard Disk size and location as 50 GB.
<img src = "image/17.png" height = 300, width = 600>  
<img src = "image/18.png" height = 300, width = 600>
Then choose English as your language. Choose Windows Server 2022 Standard Evaluation (Desktop experience)
<img src = "image/19.png" height = 300, width = 600>
<img src = "image/20.png" height = 300, width = 600>
After that, agree to license and agreements. And choose install Microsoft server operating system only (advanced) option.
<img src = "image/21.png" height = 300, width = 600>
<img src = "image/22.png" height = 300, width = 600>
After that, choose Driver Unallocated 0 option. And after that download create password for your server.
<img src = "image/23.png" height = 300, width = 600>
<img src = "image/24.png" height = 300, width = 600>
<img src = "image/25.png" height = 300, width = 600>

<h3> Ubuntu Server 22.04 Installation </h3>
To install Ubuntu 22.04.3 server, use this link:https://mirror.cherryservers.com/ubuntu-releases/releases/releases/22.04.3/
After downloading the ubuntu server, create a space in virtual box.
<img src = "image/26.png" height = 300, width = 600>
Mount the downloaded iso file and choose base memory as 8192 and number of CPUs as 2. Choose Hard Disk File Location and Size as 100 GB and then create the virtual machine.
<img src = "image/27.png" height = 300, width = 600>
<img src = "image/28.png" height = 300, width = 600> 
<img src = "image/29.png" height = 300, width = 600>
After this, do as shown in the screenshots below. The "green" and "red" color shows the option that I chose for the system configuration.
<img src = "image/30.png" height = 300, width = 600>
<img src = "image/31.png" height = 300, width = 600>
<img src = "image/32.png" height = 300, width = 600>
<img src = "image/33.png" height = 300, width = 600>
<img src = "image/34.png" height = 300, width = 600>
<img src = "image/35.png" height = 300, width = 600>
<img src = "image/36.png" height = 300, width = 600>
<img src = "image/37.png" height = 300, width = 600>
<img src = "image/38.png" height = 300, width = 600> 
<img src = "image/39.png" height = 300, width = 600>
Then set up your name, your server's name, username and password. After that, just chose the "green" option as shown in screenshot.
<img src = "image/40.png" height = 300, width = 600>
<img src = "image/41.png" height = 300, width = 600>
<img src = "image/42.png" height = 300, width = 600>
<img src = "image/43.png" height = 300, width = 600> 
<img src = "image/44.png" height = 300, width = 600>
Note: The installation will take time.

<h3> Kali Linux Installation </h3>
For kali installation, go to kali website and download the amd64 file. The zipped file will be downloaded in your download folder and then extract the folder.
<img src = "image/45.png" height = 300, width = 600>
<img src = "image/46.png" height = 300, width = 600>
<img src = "image/47.png" height = 300, width = 600>
After extracting, Choose show extension option in folder. There are two files .vbox and .vdi file. Choose .vbox file it will directly exported to virtual box. The username and password to kali machine is: kali and kali.
<img src = "image/48.png" height = 300, width = 600>
<img src = "image/49.png" height = 300, width = 600>
<img src = "image/50.png" height = 300, width = 600>
<img src = "image/51.png" height = 300, width = 600>

<h3> Creating Own Network </h3>
For creating own NAT network, go to network option in virtual box and select option Create. Name the network: AD Project and put IPv4 option as: 192.168.10.0/24 and select enable DHCP option.
<img src = "image/52.png" height = 300, width = 600>
<img src = "image/53.png" height = 300, width = 600>
After that, choose Attached to: NAT Network option and then AD Project option for every virtual machine installed above. This will ensure that all four virtual machines are in same network which will also help us to allocate the IP address for all four virtual machine. The screenshots are attached below.
<img src = "image/54.png" height = 300, width = 600>
<img src = "image/55.png" height = 300, width = 600> 
<img src = "image/56.png" height = 300, width = 600>
<img src = "image/57.png" height = 300, width = 600>

<h2> Installing Splunk Enterprise, Sysmon and Splunk Universal Forwarder </h2>
<h3> Splunk Enterprise on Ubuntu 22.04 </h3>
Now we are installing Splunk enterprise in Ubuntu server. Before that, we have to configure the IP address in the ubuntu server. To configure the network address of the ubuntu server, first we check the IP address of the server using the command: <B>ip a</B>.After that, we navigate to the file config.yaml using the command: <B>sudo nano /etc/netplan/00-installer-config.yaml</B>
<img src = "image/57-1.png" height = 300, width = 600>
After entering in the file, we set dhcp4: no and add our ubuntu server address: 192.168.10.10/24, add nameservers: 8.8.8.8 and then finally route the network from ubuntu server using the address: 192.168.10.1.(Ask myself: why this configuration) We save this configuration and to apply the changes we use the command: <B>sudo netplan apply</B>
<img src = "image/57-2.png" height = 300, width = 600>
<img src = "image/57-3.png" height = 300, width = 600>
Finally, we check ip address using command: ip a and make sure that it can access the internet using the command:<B>ping google.com</B> 
<img src = "image/57-4.png" height = 300, width = 600>
Then we have download the Splunk Enterprise in the laptop. We have to create directory called Active Directory Project and move the Splunk downloader to the folder which is later mounted to the server.
<img src = "image/58.png" height = 300, width = 600>
<img src = "image/59.png" height = 300, width = 600>
<img src = "image/59-1.png" height = 300, width = 600>
We should install VirtualBox using the command (why this): <B>sudo apt-get install virtual box</B> and<B>sudo apt-get install virtualbox-guest-utils</B>
<img src = "image/60.png" height = 300, width = 600>
<img src = "image/61.png" height = 300, width = 600>
After that, we reboot the system and create a folder called share using command:<B>mkdir share</B>
<img src = "image/62.png" height = 300, width = 600>
<img src = "image/63.png" height = 300, width = 600>
After that, we choose shared foler and then chose the Active Directory Folder.
<img src = "image/64.png" height = 300, width = 600>
<img src = "image/65.png" height = 300, width = 600>
After that I mounted Active Directory Project to the share folder using the command: sudo mount -t vboxsf -0 uid=1000,gid=1000 Active_Directory_Project share/. We entered the folder using command: cd share/ then we installed the splunk package using command: <B>sudo dpkg -i splunk-10.4.0-f798d4d49089-linux-amd64.deb</B>
<img src = "image/66.png" height = 300, width = 600>
Then we eneterd the <B>cd /opt/splunk</B> and <B>ls -la</B> and we see the splunk is installed.
<img src = "image/67.png" height = 300, width = 600>
After that set the user to splunk using the command: <B>sudo -u splunk bash</B>. After that we come out of the /opt/splunk directory and enter into bin directory to start splunk using the command: <B>cd bin and ./splunk start</B>
<img src = "image/68.png" height = 300, width = 600>
After that installation process of Splunk Enterprise begins.
<img src = "image/69.png" height = 300, width = 600>
After completing installation, we exit from the /bin directory for sometime. Then we again entered the /bin directory and start the splunk using the command: <B>sudo ./splunk enable boot-start -user splunk</B>
<img src = "image/70.png" height = 300, width = 600>
After that we access the splunk on the web using the address: http://192.168.10.10:8000
<img src = "image/71.png" height = 300, width = 600>

<h3> Splunk Forwarder and Sysmon on Windows 10 </h3>
Before installing Splunk forwarder and Sysmon we must configure the network of our windows 10.The first step is to rename the PC to target-PC. After renaming the PC, we have restart the windows 10.
<img src = "image/72.png" height = 300, width = 600>
Then we check the IP address of the machine using the command: ipconfig in command prompt.
<img src = "image/74.png" height = 300, width = 600>
After that, we should go the setting and choose Network and Internet. Then after we choose the option change adapter options.
<img src = "image/76.png" height = 300, width = 600>
After that select ethernet properties by right clicking on the Ethernet option.
<img src = "image/77.png" height = 300, width = 600>
Then we choose the Internet protocol Version 4 (TCP/IPv4) option and chose the option using following address option. Then we set network settings in following way:
IP address: 192.168.10.100
Subnet mask: 255.255.255.0
Default Gateway: 192.168.10.1
Preferred DNS Server: 8.8.8.8
<img src = "image/78.png" height = 300, width = 600>
<img src = "image/79.png" height = 300, width = 600>
And then we make sure the changes are applied using the command: ipconfig and the changes are reflected.
<img src = "image/80.png" height = 300, width = 600>
To install the Splunk forwarder, we sign in into Splunk official website and download forwarder compatible with windows 10 64 bit machine.
<img src = "image/81.png" height = 300, width = 600>
Then we install the Splunk forwarder and start configuring it. Choose an on premise Splunk Enterprise Instance.
<img src = "image/83.png" height = 300, width = 600>
Here the username is: admin. The hostname IP is ubuntu server's IP i.e. 192.168.10.10. And the port number is 9997
<img src = "image/84.png" height = 300, width = 600>
<img src = "image/86.png" height = 300, width = 600>
Finally, we install the Splunk Forwarder.
<img src = "image/87.png" height = 300, width = 600>
<img src = "image/88.png" height = 300, width = 600>
Now we have change the configuration of Sysmon. Navigate to the location:
C:\Program Files\SplunkUniversalForwarder\etc\system\local
<img src = "image/91.png" height = 300, width = 600>
After that, visit this site: https://github.com/MyDFIR/Active-Directory-Project.
<img src = "image/93.png" height = 300, width = 600>
Then open the notepad as administrator, copy the content of Splunk Inputs.conf. and save the file as inputs.conf
<img src = "image/92.png" height = 300, width = 600>
<img src = "image/94.png" height = 300, width = 600>
Then in PC, go to the services and right click on 'Local System Account'. After that, restart the SplunkForwarder service.
<img src = "image/95.png" height = 300, width = 600>
<img src = "image1/96.png" height = 300, width = 600>
To install Sysmon visit official site of Microsoft and download the file.
<img src = "image1/99.png" height = 300, width = 600>
Then open the windows PowerShell as an administrator and use the command:
cd C:\Users\kajal\Downloads\Sysmon
.\Sysmon64.exe ..\sysmonconfig.xml
This command will install the Sysmon
<img src = "image1/100.png" height = 300, width = 600>
<img src = "image1/101.png" height = 300, width = 600>

Note: Make sure Splunk Forwarder and Sysmon64 services are running.
Navigate to the Splunk and choose Indexes option. Then, name index as endpoint.
<img src = "image1/102.png" height = 300, width = 600>
<img src = "image1/103.png" height = 300, width = 600>
Then go to the Forwarding and receiving option and click configure receiving. And then configure listening port as 9997.
<img src = "image1/104.png" height = 300, width = 600>
<img src = "image1/105.png" height = 300, width = 600>
<img src = "image1/106.png" height = 300, width = 600>
And make sure the endpoint is logged into Splunk

<h3> Splunk Forwarder and Sysmon on Windows Server </h3>
Followed the same process as in Windows 10.
<img src = "image1/108.png" height = 300, width = 600>

<h2> Configuring Active Directory </h2>
<h3> Installing and Promoting Active Directory to Domain Controller </h3>
<h3> Creating Users </h3>
<h3> Logging into PC as a User of Domain Controller </h3>
<h2> Performing Attack and Generating Telemetry </h2>
<h3> Installing Hydra and Creating Password File </h3>
<h3> Enabling Remote Connection in Windows PC </h3>
<h3> Brute Force Attack on Windows PC </h3>
<h3> Querying Attack on Splunk </h3>
<h3> Installing Atomic Red Team (ART) Framework </h3>
<h3> Performing Gap Analysis using ART </h3>

