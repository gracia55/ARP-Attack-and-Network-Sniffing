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
![Screenshot 2023-09-26 205133](https://github.com/Reebak04/ARP-Attack-and-Network-Sniffing/assets/118364993/af970103-9fb9-429d-acf8-1f5d094219ca)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![380623232-557b6bad-bde9-44f0-806d-f3ed0ded972d](https://github.com/user-attachments/assets/42183c3f-5685-4dc1-b3a4-adbfb36a1992)


 ## dsniff:


In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![380623342-3129c6d9-7fe1-456b-947b-8bd9963a7bf8](https://github.com/user-attachments/assets/0c2ef14f-d640-4227-b9f5-d1c3ada7032a)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![380623405-37767cdc-ebbf-4f4c-918b-e8dc8d73a967](https://github.com/user-attachments/assets/1f596724-13dc-4929-a82a-f1ffa08ae1ad)



Invoke the wireshark and examine the various menus  and controls of the tool:
![380623536-9b8608eb-7e8e-4f59-8a79-3bf716f82d1d](https://github.com/user-attachments/assets/d7f13173-bb72-4239-806a-23b9009284d4)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
