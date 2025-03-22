[IANA 공식 문서](https://www.iana.org/assignments/protocol-numbers/protocol-numbers.xhtml)

IPv4(Internet Protocol Version 4)의 헤더에는 13개의 필드로 구성되어 있습니다.      

이중 프로토콜 필드는 8 비트 값으로 이루어져 있으며 4(전송) 계층에서 어떤 프로토콜을 사용하는지 명시하고 있습니다.         
프로토콜은 수납되는 상위 계층 프로토콜을 나타내는 식별자/유형/번호 정보를 포함합니다. 쉽게 말하면 컴퓨터 간 정보를 주고받을 때 통신방법에 대한 규약입니다. 
예를 들어 대화할 때 같은 언어를 사용해야 말이 통하는 것과 같습니다.대표적으로 사용하는 프로토콜은 ICMP(1), TCP(6), UDP(17) 입니다.    

tcp 6, udp 17, icmp, 0,1,8

# 프로토콜 번호와 프로토콜 이름

| 프로토콜 번호 | 프로토콜 이름 |
|--------------|---------------|
| 1            | ICMP          |
| 2            | IGMP          |
| 3            | GGP           |
| 4            | IPv4          |
| 5            | ST            |
| 6            | TCP           |
| 7            | CBT           |
| 8            | EGP           |
| 9            | IGP           |
| 10           | BBN-RCC-MON   |
| 11           | NVP-II        |
| 12           | PUP           |
| 13           | ARGUS         |
| 14           | EMCON         |
| 15           | XNET          |
| 16           | CHAOS         |
| 17           | UDP           |
| 18           | MUX           |
| 19           | DCN-MEAS      |
| 20           | HMP           |
| 21           | PRM           |
| 22           | XNS-IDP       |
| 23           | TRUNK-1       |
| 24           | TRUNK-2       |
| 25           | LEAF-1        |
| 26           | LEAF-2        |
| 27           | RDP           |
| 28           | IRTP          |
| 29           | ISO-TP4       |
| 30           | NETBLT        |
| 31           | MFE-NSP       |
| 32           | MERIT-INP     |
| 33           | DCCP          |
| 34           | 3PC           |
| 35           | IDPR          |
| 36           | XTP           |
| 37           | DDP           |
| 38           | IDPR-CMTP     |
| 39           | TP++          |
| 40           | IL            |
| 41           | IPv6          |
| 42           | SDRP          |
| 43           | IPv6-Route    |
| 44           | IPv6-Frag     |
| 45           | IDRP          |
| 46           | RSVP          |
| 47           | GRE           |
| 48           | MHRP          |
| 49           | BNA           |
| 50           | ESP           |
| 51           | AH            |
| 52           | I-NLSP        |
| 53           | SWIPE         |
| 54           | NARP          |
| 55           | MOBILE        |
| 56           | TLSP          |
| 57           | SKIP          |
| 58           | ICMPv6        |
| 59           | IPv6-NoNxt    |
| 60           | IPv6-Opts     |
| 61           | Any host internal protocol |
| 62           | CFTP          |
| 63           | Any local network           |
| 64           | SAT-EXPAK     |
| 65           | KRYPTOLAN     |
| 66           | RVD           |
| 67           | IPPC          |
| 68           | Any distributed file system |
| 69           | SAT-MON       |
| 70           | VISA          |
| 71           | IPCV          |
| 72           | CPNX          |
| 73           | CPHB          |
| 74           | WSN           |
| 75           | PVP           |
| 76           | BR-SAT-MON    |
| 77           | SUN-ND        |
| 78           | WB-MON        |
| 79           | WB-EXPAK      |
| 80           | ISO-IP        |
| 81           | VMTP          |
| 82           | SECURE-VMTP   |
| 83           | VINES         |
| 84           | TTP           |
| 85           | NSFNET-IGP    |
| 86           | DGP           |
| 87           | TCF           |
| 88           | EIGRP         |
| 89           | OSPFIGP       |
| 90           | Sprite-RPC    |
| 91           | LARP          |
| 92           | MTP           |
| 93           | AX.25         |
| 94           | IPIP          |
| 95           | MICP          |
| 96           | SCC-SP        |
| 97           | ETHERIP       |
| 98           | ENCAP         |
| 99           | Any private encryption scheme |
| 100          | GMTP          |
| 101          | IFMP          |
| 102          | PNNI          |
| 103          | PIM           |
| 104          | ARIS          |
| 105          | SCPS          |
| 106          | QNX           |
| 107          | A/N           |
| 108          | IPComp        |
| 109          | SNP           |
| 110          | Compaq-Peer   |
| 111          | IPX-in-IP     |
| 112          | VRRP          |
| 113          | PGM           |
| 114          | Any 0-hop protocol |
| 115          | L2TP          |
| 116          | DDX           |
| 117          | IATP          |
| 118          | STP           |
| 119          | SRP           |
| 120          | UTI           |
| 121          | SMP           |
| 122          | SM            |
| 123          | PTP           |
| 124          | ISIS over IPv4 |
| 125          | FIRE          |
| 126          | CRTP          |
| 127          | CRUDP         |
| 128          | SSCOPMCE      |
| 129          | IPLT          |
| 130          | SPS           |
| 131          | PIPE          |
| 132          | SCTP          |
| 133          | FC            |
| 134          | RSVP-E2E-IGNORE |
| 135          | Mobility Header |
| 136          | UDPLite       |
| 137          | MPLS-in-IP    |
| 138          | manet         |
| 139          | HIP           |
| 140          | Shim6         |
| 141          | WESP          |
| 142          | ROHC          |
| 143-252      | Unassigned    |
| 253          | Use for experimentation and testing |
| 254          | Use for experimentation and testing |
| 255          | Reserved      |


# protocol
프로토콜 번호 외우기 (ex Mobile 55 ~)
SIEM 에서 관리하는 프로토콜 들의 번호를 외우기 위함
1. icmp
2. igmp
3. ggp
4. ipv4
5. st
6. tcp
7. ctcp
8. egp
9. igp
10. bbn rcc monitoring
11. network voice protocol nvp
12. pup
13. emcon
14. xnet
15. chaos
16. x.25
17. performace measurement
18. reliable datagram protocol
19. heartbeat protocol
20. network management protocol
21. video conferencing protocol
22. internet protocol version 6 ipv6
23. mobile ip
24. ntp
25. mccp
26. rpc
27. sun
28. secure protocol
29. pptp
30. eigrp
31. mpls
32. ipr
33. mobile ad hoc 에드훅
34. bgp
35. rip
36. is-is
37. ospf
38. dccp
39. sctp
40. tcp/udp
41. spx
42. gtp
43. atm
44. x.400
45. x.500
53. dns
58. icmp v6
67 dhcp
79 tftp
70 gopher
71 netbios
79 finger
80 http
81 http alternate
