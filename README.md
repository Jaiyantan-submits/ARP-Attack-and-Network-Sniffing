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

<img width="896" height="114" alt="image" src="https://github.com/user-attachments/assets/dc28faa1-fd46-42b2-b933-9e0f029451fc" />


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

<img width="924" height="420" alt="image" src="https://github.com/user-attachments/assets/a4e95108-899b-47d3-ae27-00414e116672" />

 dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

<img width="930" height="394" alt="image" src="https://github.com/user-attachments/assets/3fa2b738-1148-4b3b-84fb-413c1598f5fd" />



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

<img width="766" height="125" alt="image" src="https://github.com/user-attachments/assets/860a6298-65c6-439d-b4b6-351cecbac74a" />


Invoke the wireshark and examine the various menus  and controls of the tool:
<img width="1914" height="807" alt="image" src="https://github.com/user-attachments/assets/ad71220a-98d0-4465-a980-1b71660431aa" />


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
