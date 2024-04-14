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

![Screenshot 2024-04-14 191243](https://github.com/kanagavel7/ARP-Attack-and-Network-Sniffing/assets/162578954/769b9b62-86f2-41b4-88a0-c5cf732ce43f)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![Screenshot 2024-04-14 191331](https://github.com/kanagavel7/ARP-Attack-and-Network-Sniffing/assets/162578954/958bb673-d4d1-4614-a74b-12a475c6eeb1)

 ## dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org

## OUTPUT:

![Screenshot 2024-04-14 191432](https://github.com/kanagavel7/ARP-Attack-and-Network-Sniffing/assets/162578954/367fd9c3-b342-4862-a19f-1e79a19a847f)

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![Screenshot 2024-04-14 191507](https://github.com/kanagavel7/ARP-Attack-and-Network-Sniffing/assets/162578954/0b58e402-dc22-4dff-8e12-55396d9befd5)


Invoke the wireshark and examine the various menus  and controls of the tool:

![Screenshot 2024-04-14 191643](https://github.com/kanagavel7/ARP-Attack-and-Network-Sniffing/assets/162578954/10cd7014-fbb4-4def-9741-06281764859b)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
