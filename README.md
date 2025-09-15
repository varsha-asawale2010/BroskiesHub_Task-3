# BroskiesHub_Task-3
## Task Name: Capture and Analyze Network Traffic Using Wireshark.
## Installation successfull
<img width="1919" height="976" alt="1" src="https://github.com/user-attachments/assets/7a78f79d-6deb-447e-b486-6d9f6d639c5a" />

## Start packets Capturing using wireshark
<img width="1919" height="979" alt="2" src="https://github.com/user-attachments/assets/464d767c-50bb-46d0-908d-c06616be9edb" />

## Ping server and generate some traffic
## ping website name:github.com
<img width="1919" height="764" alt="3" src="https://github.com/user-attachments/assets/83d86ae0-521e-47bf-b8b3-e3704a08f91d" />

## Filter captured packets by protocol
### Protocol 1:- http-hyper text transfer protocol
![image](https://github.com/user-attachments/assets/bbd751ee-fe57-4609-b18d-340dd0d69b09)

### protocol 2:- DNS-Domain name server

<img width="1912" height="962" alt="5" src="https://github.com/user-attachments/assets/47cdda05-5b75-4070-812d-dd7631d259ab" />

### Protocol 3:- tcp-Transmission Control Protocol
<img width="1919" height="991" alt="6" src="https://github.com/user-attachments/assets/1e992c5b-87b5-4eaf-8cb2-81d7b10cd4c1" />

 ### Protocol 4:- ICMP-Internet Control Message Protoco
<img width="1911" height="1008" alt="7" src="https://github.com/user-attachments/assets/b72cf4ec-d173-4a55-ad1b-2497f2db9b29" />


## Identifying Different Protocols

1. DNS (Domain Name System):Translates domain names github.com into  their IP addresses.
Look for packets where your computer queries a DNS server to resolve a domain name.

2. HTTP (Hypertext Transfer Protocol): Used for transferring web pages.
Identify HTTP GET or POST requests when accessing websites.

3. TCP (Transmission Control Protocol): Establishes and maintains a connection between devices for data transmission.
Notice the three-way handshake (SYN, SYN-ACK, ACK) when initiating a connection.

4. ICMP (Internet Control Message Protocol):Used for diagnostic purposes, like the ping command.
See echo request and reply packets when you ping a server.

## Export the capture here



## 8. Summarize our Findings and Packet Details
1.DNS Queries: Your computer sent DNS queries to resolve domain names, receiving corresponding IP addresses in the responses.<br>
2.HTTP Requests: When accessing websites, HTTP GET requests were sent, and responses were received, containing the requested web pages.<br>
3.TCP Handshakes: Before data transmission, TCP connections were established using the three-way handshake process.<br>
4.ICMP Packets: Using the ping command generated ICMP echo request and reply packets, indicating connectivity with the t
