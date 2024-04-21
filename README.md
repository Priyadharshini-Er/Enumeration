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

## Output:
![exp  31](https://github.com/swetha1510/Enumeration/assets/120623583/fbafbd09-fb5e-4c46-adcd-3c673f0b576d)

filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com

## Output:
![eh exp 32](https://github.com/swetha1510/Enumeration/assets/120623583/c24aa178-d134-489a-9ae0-e5e2656f7ddd)

intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.

## Output:
![exp 33](https://github.com/swetha1510/Enumeration/assets/120623583/42d53330-1b22-4434-8cb4-ce996180f72d)

inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.
## Output:
![exp 34](https://github.com/swetha1510/Enumeration/assets/120623583/ce0a9bae-e623-4817-933d-af95c4b56248)

intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.
## Output:
![exp 37](https://github.com/swetha1510/Enumeration/assets/120623583/576d6249-5613-4143-90c3-de63c1a47269)

link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.
## Output:
![exp 35](https://github.com/swetha1510/Enumeration/assets/120623583/f1f7e199-8707-404f-8907-57595d5d0f74)
cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.

## Output:
![exp 36](https://github.com/swetha1510/Enumeration/assets/120623583/68c2c067-4b1b-471e-8bb3-1b0e3d81e040)

 
# DNS Enumeration

## DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion
## OUTPUT:
![eh 31](https://github.com/swetha1510/Enumeration/assets/120623583/bc2b54a4-c0b5-4944-9855-10f4df517742)

![eh 32](https://github.com/swetha1510/Enumeration/assets/120623583/3d314f6c-7d7b-4338-9e67-34d74aaa8c10)

![eh 33](https://github.com/swetha1510/Enumeration/assets/120623583/c23045e7-86d6-4eb4-b9dd-47d2295fccc9)

### smtp-user-enum:
![eh 34](https://github.com/swetha1510/Enumeration/assets/120623583/484e22dc-6136-491a-85e9-70da7a3ea77c)

## nmap –script smtp-enum-users.nse <hostname>
![eh 35](https://github.com/swetha1510/Enumeration/assets/120623583/20d749d8-5c12-4141-b08e-239120271765)

## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

