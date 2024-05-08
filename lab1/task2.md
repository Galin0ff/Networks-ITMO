tshark -D
1. \Device\NPF_{95CB890F-9858-477C-BACD-8A4E1874B3B8} (Ethernet)
2. \Device\NPF_Loopback (Adapter for loopback traffic capture)
3. etwdump (Event Tracing for Windows (ETW) reader)

tshark -i 1 arp
Capturing on 'Ethernet'
    1   0.000000 MercusysTech_a9:73:a9 → Broadcast    ARP 60 Who has 192.168.168.105? Tell 192.168.168.1
    2   1.000331 MercusysTech_a9:73:a9 → Broadcast    ARP 60 Who has 192.168.168.105? Tell 192.168.168.1
    3   8.000066 MercusysTech_a9:73:a9 → Broadcast    ARP 60 Who has 192.168.168.108? Tell 192.168.168.1
    4   8.000066 MercusysTech_a9:73:a9 → Broadcast    ARP 60 Who has 192.168.168.101? Tell 192.168.168.1
    5   9.000285 MercusysTech_a9:73:a9 → Broadcast    ARP 60 Who has 192.168.168.108? Tell 192.168.168.1
    6   9.000285 MercusysTech_a9:73:a9 → Broadcast    ARP 60 Who has 192.168.168.101? Tell 192.168.168.1
    7  10.000134 MercusysTech_a9:73:a9 → Broadcast    ARP 60 Who has 192.168.168.106? Tell 192.168.168.1
    8  10.000134 MercusysTech_a9:73:a9 → Broadcast    ARP 60 Who has 192.168.168.108? Tell 192.168.168.1
    9  10.000134 MercusysTech_a9:73:a9 → Broadcast    ARP 60 Who has 192.168.168.107? Tell 192.168.168.1
   10  10.000162 MercusysTech_a9:73:a9 → Broadcast    ARP 60 Who has 192.168.168.101? Tell 192.168.168.1
   11  11.000096 MercusysTech_a9:73:a9 → Broadcast    ARP 60 Who has 192.168.168.106? Tell 192.168.168.1
   12  11.000096 MercusysTech_a9:73:a9 → Broadcast    ARP 60 Who has 192.168.168.107? Tell 192.168.168.1
   13  12.000169 MercusysTech_a9:73:a9 → Broadcast    ARP 60 Who has 192.168.168.105? Tell 192.168.168.1
   14  12.000169 MercusysTech_a9:73:a9 → Broadcast    ARP 60 Who has 192.168.168.106? Tell 192.168.168.1
   15  12.000169 MercusysTech_a9:73:a9 → Broadcast    ARP 60 Who has 192.168.168.107? Tell 192.168.168.1
   16  13.000276 MercusysTech_a9:73:a9 → Broadcast    ARP 60 Who has 192.168.168.105? Tell 192.168.168.1
   17  14.000373 MercusysTech_a9:73:a9 → Broadcast    ARP 60 Who has 192.168.168.105? Tell 192.168.168.1
   18  15.000196 MercusysTech_a9:73:a9 → Broadcast    ARP 60 Who has 192.168.168.102? Tell 192.168.168.1
   19  16.000157 MercusysTech_a9:73:a9 → Broadcast    ARP 60 Who has 192.168.168.102? Tell 192.168.168.1
   20  16.000157 MercusysTech_a9:73:a9 → Broadcast    ARP 60 Who has 192.168.168.105? Tell 192.168.168.1
   21  17.000250 MercusysTech_a9:73:a9 → Broadcast    ARP 60 Who has 192.168.168.102? Tell 192.168.168.1
   22  17.000250 MercusysTech_a9:73:a9 → Broadcast    ARP 60 Who has 192.168.168.105? Tell 192.168.168.1
   23  18.001652 MercusysTech_a9:73:a9 → Broadcast    ARP 60 Who has 192.168.168.105? Tell 192.168.168.1