# NetPractice

## Objectives
Learning how to configurate network of small size.<br />
For this, I'll need to learn how TCP/IP protocol works.
## Results

---
## Theory

### Ip address

Ip addresses are a combination of 4 octets separated by dots as seen below.

![Address_ScreenShot](img/ip_addresses_explanation.png?style=center)

*Reminder : an octets is composed of 8 binary digits example below*

| 128      | 64 | 32 | 16 | 8 | 4 | 2 | 1 |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| 0      | 0 | 0 | 0 | 0 | 0 | 0 | 0 |

Value of this octet = **0**

| 128      | 64 | 32 | 16 | 8 | 4 | 2 | 1 |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| 0      | 1 | 0 | 1 | 0 | 1 | 0 | 0 |

Value of this octet = **84**

| 128      | 64 | 32 | 16 | 8 | 4 | 2 | 1 |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| 1      | 1 | 1 | 1 | 1 | 1 | 1 | 1 |

Value of this octet = **255**

| 128      | 64 | 32 | 16 | 8 | 4 | 2 | 1 |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| 0      | 0 | 1 | 1 | 1 | 1 | 1 | 1 |

Value of this octet = **63** *(This is a interesting behavior to keep in mind)*


### Subnet Mask

Now, we need to understand how to assign IP addresses for computers inside of a Network.

To be able to differentiate between the Network number and the Hosts number we'll use subnetting and IP's masks.

All IP addresses possess a Mask. The syntax for a Mask is the same as for the IP address (4 octets seperated by dots).

The mask can also be written in CIDR example below.
