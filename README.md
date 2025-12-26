# AutoCore-Enterprise-Multi-site-Car-Manufacturing-Network
A complete IPv4-based enterprise network for a car manufacturing company with HQ, a manufacturing plant, and a dealership site. I implemented VLANs, OSPF for inter-site routing, HSRP, EtherChannel for redundancy, port security, ACL's, NAT-PAT, Syslog and NTP server, DHCP/DNS services, I have also done some HTML scripting for the website to make it look good. This project demonstrates all major CCNA concepts in one real-world automotive environment.

I have done HSRP for gateway redundancy but at some point when working with HSRP we have to enable interface tracking which unfortunately is not available for the IOS version I'm using in this packet tracer and the mls is also not supporting it, because of this there is a limit for some links if they get shutdown the packet doesn't reach to destination, so I have to compromise with it, otherwise it would have worked perfectly, anyway the point is to learn the usage and skill which I got by implementing this was worth it.

<img width="1378" height="713" alt="Autocore" src="https://github.com/user-attachments/assets/8d6e49a2-4527-458c-b0a4-25838252a7ef" />



<img width="1857" height="1582" alt="image" src="https://github.com/user-attachments/assets/fbdda249-f7f1-459f-b292-708ab24e193e" />
<img width="624" height="711" alt="image (1)" src="https://github.com/user-attachments/assets/b0cf3810-7bbd-4757-ac14-83fb195de8d0" />

<img width="629" height="401" alt="acl" src="https://github.com/user-attachments/assets/b94ee693-e09b-4967-8405-80bbc832d7cb" />

<img width="632" height="512" alt="NAT" src="https://github.com/user-attachments/assets/9a286546-3559-4dc7-97ec-fbc98edbe5e0" />
