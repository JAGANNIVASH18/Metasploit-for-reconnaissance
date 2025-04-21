# Metasploit-for-reconnaissance
# Metasploit
Metasploit for reconnaissance in pentesting

# AIM:

To get introduced to Metasploit Framework and to  perform reconnaissance  in pentesting .

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Find out the ip address of the attackers system

## OUTPUT:
![Screenshot 2025-04-21 105202](https://github.com/user-attachments/assets/86ba51a0-e584-424d-9464-f62ead367e28)

## Invoke msfconsole

## OUTPUT:
![Screenshot 2025-04-21 105320](https://github.com/user-attachments/assets/63e7e164-a669-48de-81a3-52c016e9cedf)

Type help or a question mark "?" to see the list of all available commands you can use inside msfconsole.

![Screenshot 2025-04-21 105356](https://github.com/user-attachments/assets/079b649b-b9c2-434c-ae97-baba1ffe83fc)

### PORT SCANNING
## msf > nmap -sT 192.168.1.100/24 -p1-1000

![Screenshot 2025-04-21 105637](https://github.com/user-attachments/assets/b7f3d688-974f-481d-9186-a331b1628cbe)

## msf > db_nmap 192.168.1.100/24

![image](https://github.com/user-attachments/assets/a1d3fa3c-3e52-439b-9442-33705ae44e73)

### kali ls -l

![Screenshot 2025-04-21 105950](https://github.com/user-attachments/assets/6c2f1baa-2e1f-4857-b983-95488fafea28)

### search

![Screenshot 2025-04-21 110118](https://github.com/user-attachments/assets/3bf64e21-323d-410d-adcb-d037146df215)

### info
![Screenshot 2025-04-21 110222](https://github.com/user-attachments/assets/2e121d08-57c9-4894-971f-bf6800f4cdc7)

### MYSQL ENUMERATION
## db_nmap -sV -sC -p 3306 <metasploitable_ip_address>
![image](https://github.com/user-attachments/assets/9d2428aa-bba5-4783-b322-a658552b5b4e)
## search 
![image](https://github.com/user-attachments/assets/d5e12707-9f73-4422-9a24-7175dc37dc15)
## use 11 Or: use auxiliary/scanner/mysql/mysql_version

![image](https://github.com/user-attachments/assets/0b58f28c-89b4-40ee-8a82-f5fb61fe73f9)
## Use the set rhosts command to set the parameter and run the module, as follows:

![image](https://github.com/user-attachments/assets/9f910374-df42-4001-a552-fccaa4510d7b)
## After scanning, you can also brute force MySQL root account via Metasploit's auxiliary(scanner/mysql/mysql_login) module.


![image](https://github.com/user-attachments/assets/17c637ee-f95f-4000-93d5-d0c61831a5b6)
## /usr/share/wordlists: set PASS_FILE /usr/share/wordlistss/rockyou.txt

![image](https://github.com/user-attachments/assets/790829a8-ea62-418e-a0e0-a044551c9d0a)

![image](https://github.com/user-attachments/assets/35500dc6-51f0-4ad4-bbd1-401517856bcb)







## RESULT:
The Metasploit framework for reconnaissance is  examined successfully
