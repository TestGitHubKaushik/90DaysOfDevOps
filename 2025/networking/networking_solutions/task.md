🧩 Task 1: Understand OSI & TCP/IP Models
🔷 What is the OSI Model?

The OSI Model (Open Systems Interconnection) is a conceptual framework that describes how data moves from one computer to another over a network.

It divides the process into 7 layers, each with its own role.

Layer	Layer Name	Purpose	Real-life Example
7	Application	Provides network services to user applications	Browsing websites using HTTP, sending emails using SMTP
6	Presentation	Converts data format and encrypts it	SSL/TLS encryption in HTTPS
5	Session	Manages and maintains sessions between devices	Your Zoom call stays connected as long as session is active
4	Transport	Ensures complete data transfer using ports	TCP (reliable) and UDP (fast) — e.g., video streaming uses UDP
3	Network	Routes packets between different networks	IP (Internet Protocol) decides where to send data
2	Data Link	Moves data between directly connected devices	Ethernet, MAC address communication
1	Physical	Transmits raw bits through cables or Wi-Fi	LAN cable, Wi-Fi signal, Router hardware
🔶 TCP/IP Model

This is a simplified version of the OSI model and is used in real-world networking (like the internet).

TCP/IP Layer	OSI Equivalent	Examples
Application Layer	Layers 5–7	HTTP, HTTPS, FTP, DNS, SSH
Transport Layer	Layer 4	TCP, UDP
Internet Layer	Layer 3	IP, ICMP
Network Access Layer	Layers 1–2	Ethernet, ARP, MAC
Example: Opening https://google.com

You type google.com in browser → Application Layer uses HTTPS.

HTTPS uses TCP (Transport Layer) to ensure reliable connection.

IP (Internet Layer) decides which route the data will take.

Network Access Layer uses your Wi-Fi or Ethernet to send bits physically.
