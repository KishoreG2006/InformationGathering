# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering


## whois:
```python
Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.
```
## output:
![WhatsApp Image 2025-03-08 at 14 15 29_6716e8ea](https://github.com/user-attachments/assets/9854730a-4d29-4c93-a548-9d321ac6518e)


## Finding Hosting Company
```
get further detail by using ip2location.com website.
```
## output:
![WhatsApp Image 2025-03-08 at 14 21 09_0db29356](https://github.com/user-attachments/assets/f8827d58-cfaf-4e16-9804-76659661dcdd)
![WhatsApp Image 2025-03-08 at 14 21 41_4618d779](https://github.com/user-attachments/assets/f1fa6896-d242-4f42-8418-18b58ff2be8a)


## History of the website:

## output:

![WhatsApp Image 2025-03-08 at 14 23 15_c0faf0e3](https://github.com/user-attachments/assets/210542bd-4233-48b7-b030-cf0358e16b6b)


# Webserver Fingerprinting:

## Netcat:
```
sudo nc ticfiber.com 80
GET / HTTP/1.1
Host: ticfiber.com
```
## output:
![image](https://github.com/user-attachments/assets/270168f7-7a59-48d4-bb34-4686a854d7ee)


## nmap:

## output:

![image](https://github.com/user-attachments/assets/7aba4d43-fd37-4b90-ace1-63df44f03678)


## Whatweb:
## output:
![image](https://github.com/user-attachments/assets/0804dd4b-297d-4bfa-9107-131b67dfd69f)

# Tracing the Location:
```
TCP Traceroute:
sudo traceroute -T ticfiber.com
```
## output:

![image](https://github.com/user-attachments/assets/d5faaa14-0a07-4b01-bb09-8bff850b7e5e)


## UDP Traceroute:
```
sudo traceroute -U ticfiber.com
```
## output:
![image](https://github.com/user-attachments/assets/fb4fe8eb-73d7-4b1d-8bc2-e7f57d3b02ff)


## ICMP Traceroute:
```
sudo traceroute ticfiber.com
```
## output:

![image](https://github.com/user-attachments/assets/a4ec4a71-0baf-4b2e-a89d-3a826af0b4c4)



## RESULT:
The information gathering techniques tools/procedure were  identified successfully.
