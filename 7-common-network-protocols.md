Common Network Protocols

1. What is a Network Protocol?
A network protocol is a set of rules and standards that allows computers and other devices to communicate and exchange data over a network.

Protocols define how data is:
- Transmitted from one device to another.
- Received and interpreted.
- Formatted and organized.
- Checked for errors.
- Secured during communication.
Example: When you open Google in your browser, several protocols work together to establish a connection, transfer webpage data and display the website.
2. Types of Common Network Protocols
Network protocols can be classified according to their functions.
A. Application Layer Protocols
These protocols provide services directly to applications and users.



1. HTTP (Hypertext Transfer Protocol)
- Used to transfer webpages between web browsers and web servers.
- It is the foundation of data communication on the World Wide Web.
- Default port: 80.
- Example: Opening a website using HTTP.




2. HTTPS (Hypertext Transfer Protocol Secure)
- Secure version of HTTP.
- Uses encryption through TLS to protect communication.
- Protects sensitive information such as passwords and payment details.
- Default port: 443.




3. FTP (File Transfer Protocol)
- Used to transfer files between computers over a network.
- Supports uploading and downloading files.
- Commonly uses ports 20 and 21.
- Example: Uploading website files to a web server.



4. SMTP (Simple Mail Transfer Protocol)
- Used for sending emails.
- Transfers emails from email clients to mail servers and between mail servers.
- Common ports: 25, 587 and 465.
- Example: Sending an email using Gmail.



5. POP3 (Post Office Protocol Version 3)
- Used to retrieve emails from a mail server.
- Traditionally downloads emails to a local device.
- Ports: 110 and 995 (secure).



6. IMAP (Internet Message Access Protocol)
- Used to access and manage emails stored on a mail server.
- Synchronizes emails across multiple devices.
- Ports: 143 and 993 (secure).



7. DNS (Domain Name System)
- Converts domain names into IP addresses.
- Helps computers locate websites and network services.
- Commonly uses port 53.
- Example: Converts google.com into an IP address.


8. DHCP (Dynamic Host Configuration Protocol)
- Automatically assigns IP addresses to devices.
- Provides network configuration such as subnet mask, gateway and DNS server.
- Uses UDP ports 67 and 68.
- Example: Your Wi-Fi router automatically assigns an IP address to your phone.



B. Transport Layer Protocols
These protocols are responsible for delivering data between applications running on different devices.

9. TCP (Transmission Control Protocol)
- Provides reliable data transmission.
- Establishes a connection before sending data.
- Ensures data arrives in the correct order.
- Detects lost data and retransmits it.
- Example: Web browsing, email and file transfers.
10. UDP (User Datagram Protocol)
- Provides faster, connectionless data transmission.
- Does not guarantee delivery or correct ordering.
- Has less overhead than TCP.
- Example: Online gaming, live video streaming and voice calls.
Difference between TCP and UDP
TCP	UDP
Connection-oriented	Connectionless
Reliable delivery	Delivery not guaranteed
Maintains data order	No ordering guarantee
More overhead	Less overhead
Generally slower	Generally faster
Web browsing, email	Gaming, live streaming

C. Internet Layer Protocols
These protocols are responsible for addressing and routing data across networks.

11. IP (Internet Protocol)
- Responsible for addressing and routing packets.
- Helps data travel from source to destination.
- Two main versions:
  - IPv4: Uses 32-bit addresses.
  - IPv6: Uses 128-bit addresses.
12. ICMP (Internet Control Message Protocol)
- Used for sending network error and diagnostic messages.
- Helps identify network connectivity problems.
- Commonly used by the ping command.
- Example: Checking whether a server is reachable.
13. ARP (Address Resolution Protocol)
- Converts an IPv4 address into a MAC address on a local network.
- Helps devices identify the physical address of another device.
- Example: Finding the MAC address of a computer on a LAN.
D. Security and Remote Access Protocols
14. SSH (Secure Shell)
- Used to access and control remote computers securely.
- Provides encrypted communication.
- Default port: 22.
- Example: Remotely managing a Linux server.
15. Telnet
- Used to access remote computers through a command-line interface.
- Sends data without encryption.
- Default port: 23.
- It is generally replaced by SSH because of security risks.
16. SSL/TLS (Secure Sockets Layer / Transport Layer Security)
- Provides encryption and secure communication over networks.
- Protects sensitive information during transmission.
- TLS is the modern standard; SSL is outdated and insecure.
- Used in HTTPS and other secure services.

3. Summary of Common Network Protocols and Port Numbers
This table is particularly important for examinations.
Protocol	Full form / Purpose	Port
HTTP	Web communication	80
HTTPS	Secure web communication	443
FTP	File transfer	20, 21
SSH	Secure remote access	22
Telnet	Remote access	23
SMTP	Sending emails	25
DNS	Domain name resolution	53
DHCP	Automatic IP assignment	67, 68
TFTP	Simple file transfer	69
POP3	Receiving emails	110
NTP	Time synchronization	123
IMAP	Email access and synchronization	143
SNMP	Network management	161, 162
LDAP	Directory services	389
SMB	File and printer sharing	445
RDP	Remote Desktop Protocol	3389

Note: Port numbers shown are standard or commonly assigned ports. Some protocols support different ports and transport configurations.
4. How These Protocols Work Together
Consider what happens when you open a website such as Google.

1. DNS: Finds the IP address associated with the website's domain name.
2. TCP: Establishes a reliable connection (for traditional HTTPS over TCP).
3. TLS: Establishes an encrypted connection.
4. HTTPS: Requests and receives webpage information.
5. IP: Routes packets between your device and the web server.
6. HTTP response: The browser receives the webpage content and displays it.
Modern HTTP/3 uses QUIC over UDP instead of TCP, with TLS integrated into QUIC.