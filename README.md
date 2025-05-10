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


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
From kali linux issue the command : sudo arpspoof -i enp0s3 -t dsniff:
![image](https://github.com/user-attachments/assets/b9c6691b-81ac-4d29-8a53-fdd9ef3aedcc)







In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![image](https://github.com/user-attachments/assets/9ea56c90-e04f-4415-9fcb-a1a94754b67e)



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/user-attachments/assets/f6ba2584-32a0-407e-b3aa-b69e2cafa55b)
Invoke the wireshark and examine the various menus and controls of the tool:
![image](https://github.com/user-attachments/assets/155d0c0e-3ab2-44e4-98a3-827a37af390b)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully

Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
