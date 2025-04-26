# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks
### NAME : G LEKASRI
### REGISTER NUMBER : 212223100025
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
![eth1](https://github.com/user-attachments/assets/5c43564f-5272-4c1e-8392-3889c1f68762)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![eth2](https://github.com/user-attachments/assets/3912e5fa-41f0-43e7-abc9-7f10f494c6d3)

 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![eth3](https://github.com/user-attachments/assets/7a966afe-3fe7-4bcd-974f-4090c2b19714)



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![eth4](https://github.com/user-attachments/assets/035021f0-2b09-49af-a0d0-76d74d837865)


Invoke the wireshark and examine the various menus  and controls of the tool:
![eth5](https://github.com/user-attachments/assets/2d7584f0-b986-4bf0-b2df-b64cb18086b5)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
