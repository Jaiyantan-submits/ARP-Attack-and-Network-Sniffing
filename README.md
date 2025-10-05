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
<img width="843" height="129" alt="image" src="https://github.com/user-attachments/assets/a2bdf3bd-613d-46a8-8aeb-cddbad73a34c" />


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

<img width="924" height="420" alt="image" src="https://github.com/user-attachments/assets/53bdd568-01f3-4d30-8b2d-f1e143f7d3c1" />


 dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

<img width="930" height="394" alt="image" src="https://github.com/user-attachments/assets/4a63e947-b360-484f-8eed-8cb2ce1d344a" />



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

<img width="766" height="125" alt="image" src="https://github.com/user-attachments/assets/e61e59de-9557-410a-8195-da210e4cecff" />

Invoke the wireshark and examine the various menus  and controls of the tool:

<img width="1914" height="807" alt="image" src="https://github.com/user-attachments/assets/3caec6b8-d422-44d3-9ed5-8725e0c1ab3f" />


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
