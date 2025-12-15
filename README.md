
<img width="1314" height="706" alt="autocore" src="https://github.com/user-attachments/assets/009730b6-81f6-429a-9c25-87261bb43f94" />



# AutoCore-Enterprise-Multi-site-Car-Manufacturing-Network
A complete IPv4-based enterprise network for a car manufacturing company with HQ, a manufacturing plant, and a dealership site. I implemented VLANs, OSPF for inter-site routing, HSRP, EtherChannel for redundancy, port security, ACLs, DHCP/DNS/NAT services. This project demonstrates all major CCNA concepts in one real-world automotive environment.

Currently I'm still working on this project to add ACL's, NAT-PAT, Syslog and NTP server, I have done HSRP for gateway redundancy but at some point when working with HSRP we have to enable interface tracking which unfortunately is not available for the IOS version I'm using in this packet tracer and the mls is also not supporting it, because of this there is a limit for some links if they get shutdown the packet doesn't reach to destination, so I have to compromise with it, otherwise it would have worked perfectly, anyway the point is to learn the usage and skill which I got by implementing this was worth it.
