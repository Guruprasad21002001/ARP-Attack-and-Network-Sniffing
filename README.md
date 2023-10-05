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
![image](https://github.com/Karthikeyan21001828/ARP-Attack-and-Network-Sniffing/assets/93427303/d3832502-a8af-4b13-ab74-6ebbdcba5d97)




From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/Karthikeyan21001828/ARP-Attack-and-Network-Sniffing/assets/93427303/d9c0dc16-084d-4f31-87b5-e17fe466d684)


 ## dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/Karthikeyan21001828/ARP-Attack-and-Network-Sniffing/assets/93427303/f93d286a-5da1-45a7-907d-e13c7c7d15c0)


In Kali issue the following commands:

sudo dsnifff
## OUTPUT:
![image](https://github.com/Karthikeyan21001828/ARP-Attack-and-Network-Sniffing/assets/93427303/390b7d5a-e50f-479b-be21-a52c2119b7ee)




Invoke the wireshark and examine the various menus  and controls of the tool:

## OUTPUT:
![image](https://github.com/Karthikeyan21001828/ARP-Attack-and-Network-Sniffing/assets/93427303/18e60160-2021-46f4-a34c-8744fa69cb5f)

## Ettercap
Ettercap supports active and passive dissection of many protocols (even encrypted ones) and includes many feature for network and host analysis.
Ettercap can be used as sniffing tool as illustrated below:

## OUTPUT:
![image](https://github.com/Karthikeyan21001828/ARP-Attack-and-Network-Sniffing/assets/93427303/94c14ed1-c5ed-40b4-8f57-c53c07bfae76)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully# ARP-Attack-and-Network-Sniffing



