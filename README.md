# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:
![image](https://github.com/Pranav-AJ/ARP-Attack-and-Network-Sniffing/assets/118904526/d70510ab-90dd-4bf9-83f6-eb202c78bc36)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/Pranav-AJ/ARP-Attack-and-Network-Sniffing/assets/118904526/facb152e-d4b5-4939-b593-3a9f8ae17377)


 dsniff:In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org

 ## OUTPUT:
![image](https://github.com/Pranav-AJ/ARP-Attack-and-Network-Sniffing/assets/118904526/7df1b1bd-186e-43e6-93c0-091ab8199c79)


Invoke the wireshark and examine the various menus  and controls of the tool:

## OUTPUT:
![image](https://github.com/Pranav-AJ/ARP-Attack-and-Network-Sniffing/assets/118904526/a93ffeac-59d1-4472-b086-32701d25c817)






## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
