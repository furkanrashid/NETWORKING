1. What is IP Subnetting?
IP Subnetting is the process of dividing a large network into smaller networks called subnets (sub-networks).

It helps network administrators manage IP addresses efficiently, improve network performance, and organize devices into different networks.

Example:

Suppose an organization has a network with 256 IP addresses. Instead of using all addresses in one network, it can divide the network into four smaller subnets.
One large network
192.168.1.0/24

256 total addresses


Subnet 1

192.168.1.0/26

64 addresses


Subnet 2

192.168.1.64/26

64 addresses


Subnet 3

192.168.1.128/26

64 addresses


Subnet 4

192.168.1.192/26

64 addresses




2. Why do we need subnetting?
Subnetting is important for several reasons:
1. Efficient IP utilization: Reduces wastage of IP addresses.
2. Network management: Makes it easier to manage large networks.
3. Improved security: Different departments can be separated into different subnets.
4. Reduced network traffic: Helps limit broadcast traffic within each subnet.
5. Better performance: Makes network administration and troubleshooting easier.
3. What is a Subnet Mask?
A Subnet Mask is a 32-bit number used to identify which portion of an IP address represents the network and which portion represents the host.

An IPv4 address contains 32 bits.

Example:

IP Address: 192.168.1.10

Subnet Mask: 255.255.255.0
Network portion	Host portion
192.168.1	10

In this example:
- Network ID: 192.168.1.0
- Host ID: 10
- Subnet Mask: 255.255.255.0
4. CIDR Notation
CIDR stands for Classless Inter-Domain Routing.

It represents the subnet mask using a slash followed by a number.

Example:

192.168.1.10/24

Here:
- /24 means 24 bits are reserved for the network portion.
- Remaining 8 bits are reserved for the host portion.
Some common CIDR notations:
CIDR	Subnet Mask
/8	255.0.0.0
/16	255.255.0.0
/24	255.255.255.0
/25	255.255.255.128
/26	255.255.255.192
/27	255.255.255.224
/28	255.255.255.240
/29	255.255.255.248
/30	255.255.255.252