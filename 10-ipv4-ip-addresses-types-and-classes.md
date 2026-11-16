ipv4 addresses with types and class
IPv4 Address – Types and Classes
1. What is an IPv4 Address?

IPv4 (Internet Protocol Version 4) is a 32-bit logical address used to identify devices on a network. It helps computers communicate with each other over the internet or a local network.

An IPv4 address consists of 32 bits divided into 4 groups, called octets. Each octet contains 8 bits.

Example:
192.168.1.10

192
8 bits

168
8 bits

1
8 bits

10
8 bits

8 + 8 + 8 + 8 = 32 bits

    IPv4 length: 32 bits

    Total octets: 4

    Each octet range: 0–255

    Address format: Decimal notation (e.g. 192.168.1.1)

2. Types of IPv4 Addresses

IPv4 addresses are mainly divided into two types based on their accessibility.
A. Public IP Address

A public IP address is an address that is globally unique and used to identify a device or network on the internet.

Features:

    Used for communication over the internet.

    Assigned by an ISP (Internet Service Provider).

    Globally routable.

    Can be accessed from the internet, subject to firewall and network settings.

Example: 8.8.8.8
B. Private IP Address

A private IP address is used within a local network, such as a home, school, or office network.

Features:

    Used for communication within a local network.

    Cannot be directly routed over the public internet.

    Can be reused in different private networks.

    Usually assigned by a router using DHCP.

Private IP address ranges:

Class
	

Private IP range

Class A
	

10.0.0.0 – 10.255.255.255

Class B
	

172.16.0.0 – 172.31.255.255

Class C
	

192.168.0.0 – 192.168.255.255

Example: 192.168.1.5
3. Classes of IPv4 Addresses

IPv4 addresses are traditionally divided into five classes: A, B, C, D and E.

The classes are determined by the first octet of the IP address.
IPv4 address classes
A

Class A

First octet: 1–126 · Large networks
B

Class B

First octet: 128–191 · Medium networks
C

Class C

First octet: 192–223 · Small networks
D

Class D

First octet: 224–239 · Multicasting
E

Class E

First octet: 240–255 · Experimental / reserved
Class A

    First octet range: 1–126

    Default subnet mask: 255.0.0.0

    Network bits: 8

    Host bits: 24

    Used for very large networks.

Example: 10.1.2.3
Class B

    First octet range: 128–191

    Default subnet mask: 255.255.0.0

    Network bits: 16

    Host bits: 16

    Used for medium-sized networks.

Example: 172.16.5.10
Class C

    First octet range: 192–223

    Default subnet mask: 255.255.255.0

    Network bits: 24

    Host bits: 8

    Used for small networks.

Example: 192.168.1.10
Class D

    First octet range: 224–239

    Used for multicast communication.

    Does not have a default subnet mask for normal classful addressing.

Example: 224.0.0.1
Class E

    First octet range: 240–255

    Reserved for experimental and research purposes.

    Not used for normal host addressing.

Example: 240.0.0.1
4. Important Comparison Table

Class
	

First octet
	

Default subnet mask
	

Purpose

A
	

1–126
	

255.0.0.0
	

Large networks

B
	

128–191
	

255.255.0.0
	

Medium networks

C
	

192–223
	

255.255.255.0
	

Small networks

D
	

224–239
	

Not applicable
	

Multicast

E
	

240–255
	

Not applicable
	

Experimental

Note: 127.x.x.x is reserved for loopback testing, such as 127.0.0.1. The address 0.x.x.x is also reserved for special purposes.
5. Difference Between IP Address Types and Classes

Types
	

Classes

Public and Private
	

A, B, C, D, E

Based on accessibility
	

Based on address range and purpose

Used to identify internet or local network addresses
	

Traditionally used to divide networks by size and function
6. Important Points for Exams

    IPv4 is a 32-bit addressing system.

    IPv4 contains four octets.

    Each octet consists of 8 bits.

    The valid octet range is 0–255.

    IPv4 has five traditional classes: A, B, C, D and E.

    Class A is used for large networks.

    Class B is used for medium networks.

    Class C is used for small networks.

    Class D is used for multicast.

    Class E is reserved for experimental purposes.