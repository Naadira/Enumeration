# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 

# AIM:

To use Google for gathering information and perform enumeration of targets

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

site: This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com
![image](https://github.com/Naadira/Enumeration/assets/128135126/5d923011-476d-40c0-aba6-624040977712)

filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com
![image](https://github.com/Naadira/Enumeration/assets/128135126/23b86f90-c3f8-4591-8a6f-fabe44d0b0a6)

intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.
![image](https://github.com/Naadira/Enumeration/assets/128135126/843f9daf-44eb-4e4e-bfde-691425163065)

inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.
![image](https://github.com/Naadira/Enumeration/assets/128135126/212e039e-367e-494f-a7e5-67f66346ee9a)

intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.
![image](https://github.com/Naadira/Enumeration/assets/128135126/9b28f3a3-cdcd-4835-a083-2421ff17ecec)

link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.
![image](https://github.com/Naadira/Enumeration/assets/128135126/8adfa81d-89e9-44a2-bda0-710ee91c2b0d)

cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.
![image](https://github.com/Naadira/Enumeration/assets/128135126/39ce374d-a7dc-4384-b5af-964f96471dd4)
 
#DNS Enumeration ##DNS Recon provides the ability to perform: Check all NS records for zone transfers Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT) Perform common SRV Record Enumeration Top level domain expansion ## OUTPUT
![image](https://github.com/Naadira/Enumeration/assets/128135126/3d0b3baf-feed-4959-89be-b2d94ce8da69)
![image](https://github.com/Naadira/Enumeration/assets/128135126/b934c51b-29ac-49df-a759-6a3dc3eaec8b)
##dnsenum Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record). Get the namservers (threaded). Get the MX record (threaded). Perform axfr queries on nameservers and get BIND versions(threaded). Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”). Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded). Calculate C class domain network ranges and perform whois queries on them (threaded). Perform reverse lookups on netranges (C class or/and whois netranges) (threaded). Write to domain_ips.txt file ip-blocks. This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.
![image](https://github.com/Naadira/Enumeration/assets/128135126/e4c026ce-7f5d-489d-a42d-7b6065cbf716)
##smtp-user-enum Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.
![image](https://github.com/Naadira/Enumeration/assets/128135126/2c0462f7-8890-42eb-904e-e4c2b2eabda3)
![image](https://github.com/Naadira/Enumeration/assets/128135126/e219964b-b81b-426f-b00a-57b5ef9dd5cf)
In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd: select any username in the first column of the above file and check the same #Telnet for smtp enumeration Telnet allows to connect to remote host based on the port no. For smtp port no is 25 telnet 25 to connect and issue appropriate commands
![image](https://github.com/Naadira/Enumeration/assets/128135126/a89ae351-11d2-4004-adde-ac0e875b7368)

##smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.


In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same


#Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
  
 ##Output
![image](https://github.com/Naadira/Enumeration/assets/128135126/f57ac1c1-b4c3-4713-af50-8ad66c5e004f)

## nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.
## OUTPUT:
![image](https://github.com/Naadira/Enumeration/assets/128135126/ed23f6e0-a3bc-4feb-ba24-ec01caf536f5)


## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

