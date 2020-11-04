# Open Systems Interconnection Model

The OSI Model is a conceptual model created by the International Organization for Standardization. It enables diverse communication systems to communicate using standard protocols.

The following table presents the model's layers, their functions and protocols associated.


|      Layer      |                             Functions                            |                                              Protocols                                              |
|:---------------:|:----------------------------------------------------------------:|:---------------------------------------------------------------------------------------------------:|
| 7.Application  | Human-computer interaction; applications access network services | DNS, WWW/HTTP, P2P, EMAIL/POP, SMTP, Telnet, FTP                                                    |
| 6.Presentation | Data representation and encryption                               | HTML, DOC, JPEG, MP3, AVI, Sockets                                                                  |
| 5.Session      | Interhost communication - controlling ports and sessions         | Session establishment in TCP, SIP, RTP, RPC-Named pipes                                             |
| 4.Transport    | End-to-end connections and reliability                           | TCP, UDP, SCTP, SSL, TLS                                                                            |
| 3.Network      | Path determination and logical addressing                        | IP, ARP, IPsec, ICMP, IGMP, OSPF                                                                    |
| 2.Data link    | Physical Addressing - format of data                             | Ethernet, 802.11, MAC/LLC, VALN, ATM, HDP, Fibre Channel, Frame Relay, HDLC, PPP, Q.921, Token Ring |
| 1.Physical     | Media, signal and binary transmission                            | RS-232, RJ45, V.34, 100BASE-TX, SDH, DSL, 802.11                                                    |