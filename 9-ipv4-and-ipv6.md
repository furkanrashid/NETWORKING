IPv4 and IPv6 (Internet Protocol Versions 4 and 6)
IP (Internet Protocol) is a set of rules used for communication between devices over a network. Every device connected to a network is assigned an IP address that helps identify it and deliver data to the correct destination.

There are two main versions of IP:
1. IPv4 (Internet Protocol Version 4)
2. IPv6 (Internet Protocol Version 6)
1. IPv4 (Internet Protocol Version 4)
IPv4 is the fourth version of the Internet Protocol. It is widely used to identify devices and enable communication over the internet and local networks.

Definition: IPv4 is a network protocol that uses a 32-bit address to uniquely identify a device on an IP network.

Features of IPv4:
- Uses a 32-bit address.
- Written in decimal format.
- Divided into four groups called octets.
- Each octet contains 8 bits.
- Each octet is separated by a dot (.).
- Supports approximately 4.3 billion unique addresses.
Example:
192.168.1.1
192
8 bits
168
8 bits
1
8 bits
1
8 bits

4 octets × 8 bits = 32 bits
IPv4 address range:
- Minimum: 0.0.0.0
- Maximum: 255.255.255.255
Advantages of IPv4:
- Easy to understand and configure.
- Widely supported by networking devices.
- Compatible with most existing networks.
Disadvantages of IPv4:
- Limited number of available addresses.
- Requires techniques such as NAT to conserve public IP addresses.
- Security features are not inherently built into every IPv4 implementation.
2. IPv6 (Internet Protocol Version 6)
IPv6 is the sixth version of the Internet Protocol. It was introduced to overcome the limitation of IPv4 addresses.

Definition: IPv6 is a network protocol that uses a 128-bit address to identify devices and enable communication over IP networks.

Features of IPv6:
- Uses a 128-bit address.
- Written in hexadecimal format.
- Divided into eight groups.
- Each group contains 16 bits.
- Groups are separated by colons (:).
- Provides an extremely large number of IP addresses.
Example:
2001:0db8:85a3:0000:0000:8a2e:0370:7334
2001
16 bits

0db8
16 bits

85a3
16 bits

0000
16 bits

0000
16 bits

8a2e
16 bits

0370
16 bits

7334
16 bits

8 groups × 16 bits = 128 bits
IPv6 address capacity:

IPv6 supports approximately \(3.4 \times 10^{38}\) addresses.

Advantages of IPv6:
- Provides a huge number of IP addresses.
- Supports automatic address configuration.
- Has improved support for network routing.
- Supports IPsec security mechanisms.
- Reduces the need for NAT in many network designs.
Disadvantages of IPv6:
- More complex address format.
- Not all older devices support it.
- Migration from IPv4 requires planning and configuration.
3. Difference between IPv4 and IPv6
Feature	IPv4	IPv6
Full form	Internet Protocol Version 4	Internet Protocol Version 6
Address size	32-bit	128-bit
Format	Decimal	Hexadecimal
Groups	4 octets	8 groups
Separator	Dot (.)	Colon (:)
Example	192.168.1.1	2001:db8::1
Address capacity	4.3 billion approx.	3.4 × 10³⁸ approx.
Configuration	Manual or DHCP	SLAAC, DHCPv6 or manual
NAT	Commonly used	Generally not required
Header	Variable length	Fixed 40 bytes

4. Why was IPv6 introduced?
IPv6 was introduced mainly because IPv4 has a limited number of IP addresses.

As the number of internet-connected devices increased, IPv4 addresses started becoming insufficient.

For example:
- Computers
- Smartphones
- Smart TVs
- Smartwatches
- IoT devices
IPv6 provides a much larger address space to accommodate the growing number of internet-connected devices.
5. Easy way to remember
32
IPv4

32-bit · Decimal · Dots · 4 groups

128
IPv6

128-bit · Hexadecimal · Colons · 8 groups


