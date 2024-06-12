# NIC (Network Interface Card). 
![NIC](../image/2-Network-Interface-Card-NIC.png)
> Fonte : https://www.researchgate.net/profile/Abdul-Hadi-Alaidi/publication/346108941/figure/fig3/AS:989391652667392@1612900760035/2-Network-Interface-Card-NIC.png

## It has a logic adress: 
* (IP - Internet Protocol) 
## And also a physic adress:
* (MAC - Media Access Control)
## SWITCH
* 24 to 48 ports. In which comutes (exchange or fowarding of information) the packages between devices.
## ROUTER
* Responsible for researching the best internet route to send packages from sender to recipient in the shortest possible time.
## MODEM
* Those ISPs provides internet to your house with this device, in which is a door for you to access the internet.

# STRUCTURED CABLING (STANDARDS)
### Standards that define how the organizations of their peripheral wires will be, enabling better organization and performance on the network.
* NBR 14.565.
* ANSI/TIA 568.
* ANSI/TIA 569.
## TWISTED PAIR
* UTP and STP (shielded).
## COAXIAL CABLE
* It is composed of copper wires, with a central wire, responsible for being the conductor of the electrical pulse, metallic mesh made in isolation and a plastic shield against external interference.
## OPTICAL FIBER
## RACK

# OSI and TCP/IP Model.
![TCP/IP VS OSI](../image/TCPOSI.png)
> Fonte: https://www.dltec.com.br/blog/redes/diferenca-entre-modelo-osi-e-tcp-ip/
## Layers
 * Aplication(Port) -> Protocols: DNS(53), SSH(22), HTTP(80), HTTPS(443), FTP(21), SMTP(25), IMAP(143), DHCP(67/68), NTP(123), etc.
 * Apresentation -> Responsible for translating, encrypting and compressing data so that it can be transferred efficiently and understandably between different systems. Protocols -> TLS, SSL.
 * Session -> Responsible for establishing, managing and terminating sessions between two machines that are communicating
   Protocols -> NetBIOS, PPTP, etc.
 * Transport -> SEGMENT. TCP(Connection-oriented protocol that provides reliable data delivery, flow control, and congestion control.)
             -> UDP(Connectionless protocol that provides fast data delivery but no guarantees of reliability or order.)
 
 * Network -> PROTOCOL IP(IPV4/IPV6) (PACKAGES ROUTER TO ROUTER) Responsible for determining the physical path that data must follow to reach its destination. It manages the logical addressing, routing and forwarding of packets, ensuring that data is transmitted correctly across different networks.
 * Link -> The data link layer organizes data into units called "frames". Each frame contains a header and trailer in addition to the top layer data. The link layer, therefore, plays a fundamental role in network communication, providing the basis for the secure and efficient transfer of data between devices on the same local network.
        -> Uses MAC (Media Access Control) addresses to identify devices on the local network. Each device has a unique MAC address.
        -> Protocols: Ethernet, Wi-Fi (IEEE 802.11) 
