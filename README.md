# High-Level-Design

## What’s system design?

Low level design covers the structure of code in a given component. However, a large scale system will have multiple components / services. High level design is about the optimal design of which components to have and how they interact for a fast and efficient system.

## System Design 101

Internet works on IP-addresses. IP address is the unique identifier assigned to each device that is capable of connecting to the internet. The Internet Corporation for Assigned Names and Numbers (ICANN), a non profit organization maintains and administers these unique identifiers across world. Internet Assigned Numbers Authority (IANA), a division of the ICANN generates IP addresses and then allocates blocks of them to regional internet registries (RIRs). The RIRs then distribute the blocks to internet service providers (ISPs), who use Dynamic Host Configuration Protocol (DHCP) to assign individual IP addresses to their customers.

[IP addresses](https://www.fortinet.com/resources/cyberglossary/what-is-ip-address#:~:text=A%20dynamic%20IP%20address%20is,a%20home%20or%20an%20organization.) have two distinct versions or standards. The Internet Protocol version 4 (IPv4, 32 bit) address is the older of the two, which has space for up to 4 billion IP addresses and is assigned to all computers. The more recent Internet Protocol version 6 (IPv6, 128 bit) has space for trillions of IP addresses, which accounts for the new breed of devices in addition to computers.

When we want to expose website to the outside world, the machine that running the website need to have public and static IP address so that the IP address does not change and is accessible through internet. Since humans cannot easily remember IP addresses to access websites, so like saving contacts with names, each site is also assigned a name called URL/domain name. These domain name can be bought from the domain registrars like Namecheap, GoDaddy etc. The registrar acts as an intermediary between you (the domain registrant) and the RIR. The RIR is responsible for maintaining a centralized database of all registered domain names within a specific top-level domain (TLD) such as .com, .org, etc. ICANN oversees these registries.
