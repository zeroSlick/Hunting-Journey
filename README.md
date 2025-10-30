# Hunting-Journey
***USE AS PER  YOUR KNOWLEDGE IT HARM TO YOU ***
FLAG:-
>.... file overwrite
>>...append 
filedescriptor  it is a number ..... the number identify the file and open 
in linux every thing os file ........... ghum gaya na dimag.

..

PORT Scanning
    1.nmap
    2.hping2 / hping3    .... network scan and packet crafting
      type of scan
      
DNS Record Types
│
├── Address Mapping Records
│   ├── A       → Maps domain name to IPv4 address
│   └── AAAA    → Maps domain name to IPv6 address
│
├── Mail Related Records
│   ├── MX      → Mail Exchange (mail server for domain)
│   ├── SPF     → Defines allowed mail servers (in TXT)
│   └── TXT     → Can include SPF, DKIM, DMARC info
│
├── Name/Authority Records
│   ├── NS      → Authoritative Name Server for domain
│   ├── SOA     → Start of Authority (admin info, serial, refresh)
│   └── CNAME   → Canonical Name (alias to another domain)
│
├── Reverse & Service Records
│   ├── PTR     → Pointer Record (IP → domain, reverse DNS)
│   └── SRV     → Service Record (service and port info)
│
└── Security Records (DNSSEC)
    ├── RRSIG   → DNSSEC signature
    ├── DNSKEY  → Public key for DNSSEC
    ├── DS      → Delegation signer (links parent & child zones)
    └── NSEC    → Proves nonexistence of a record


layer information

OSI Model (Open Systems Interconnection)
│
├── Layer 1: Physical Layer
│   │
│   ├── Simple Definition:
│   │   Transfers raw bits (0s and 1s) over cables or wireless signals.
│   │
│   ├── Devices:
│   │   ├── Hub
│   │   ├── Repeater
│   │   ├── Modem
│   │   ├── Cables (UTP, STP, Coaxial, Fiber Optic)
│   │   └── Connectors (RJ-45, RJ-11)
│   │
│   ├── Transmission Media:
│   │   ├── Wired: UTP, STP, Coaxial, Fiber
│   │   └── Wireless: Radio waves, Microwaves, Infrared
│   │
│   ├── Protocols/Standards:
│   │   ├── Ethernet Physical Standards (IEEE 802.3)
│   │   └── Bluetooth, Wi-Fi Physical Specs
│   │
│   └── Data Form: **Bits**
│
├── Layer 2: Data Link Layer :- MAC address 
│   │
│   ├── Simple Definition:
│   │   Provides node-to-node communication and detects errors in frames.
│   │
│   ├── Sublayers:
│   │   ├── MAC (Media Access Control)
│   │   └── LLC (Logical Link Control)
│   │
│   ├── Devices:
│   │   ├── Switch
│   │   ├── Bridge
│   │   └── Network Interface Card (NIC)
│   │
│   ├── Protocols:
│   │   ├── Ethernet (IEEE 802.3)
│   │   ├── PPP
│   │   ├── HDLC
│   │   └── Frame Relay
│   │
│   ├── Address Type: MAC Address
│   └── Data Form: **Frames**
│
├── Layer 3: Network Layer :- Ip Address
│   │
│   ├── Simple Definition:
│   │   Responsible for routing data packets between different networks.
│   │
│   ├── Devices:
│   │   ├── Router
│   │   └── Layer 3 Switch
│   │
│   ├── Protocols:
│   │   ├── IP (IPv4, IPv6)
│   │   ├── ICMP
│   │   ├── ARP / RARP
│   │   ├── OSPF , BGP 
│   │   └── RIP
│   │
│   ├── Address Type: IP Address
│   └── Data Form: **Packets**
│
├── Layer 4: Transport Layer
│   │
│   ├── Simple Definition:
│   │   Ensures reliable data transfer, flow control, and error recovery.
│   │
│   ├── Functions:
│   │   ├── Segmentation and reassembly
│   │   ├── Flow and error control
│   │   └── Port addressing
│   │
│   ├── Protocols:
│   │   ├── TCP (Transmission Control Protocol)
│   │   └── UDP (User Datagram Protocol)
│   │
│   └── Data Form: **Segments (TCP)** / **Datagrams (UDP)**
│
├── Layer 5: Session Layer
│   │
│   ├── Simple Definition:
│   │   Manages and maintains sessions between devices during communication.
│   │
│   ├── Functions:
│   │   ├── Establish, manage, and terminate sessions
│   │   ├── Synchronization
│   │   └── Dialog control
│   │
│   ├── Protocols:
│   │   ├── NetBIOS
│   │   ├── RPC (Remote Procedure Call)
│   │   ├── PPTP
│   │   └── SIP (for VoIP)
│   │
│   └── Data Form: **Data**
│
├── Layer 6: Presentation Layer :- unstructured to structured data me convert krna .
│   │
│   ├── Simple Definition:
│   │   Translates data between application and network formats; handles encryption and compression.
│   │
│   ├── Functions:
│   │   ├── Data formatting and translation
│   │   ├── Data encryption/decryption
│   │   └── Compression
│   │
│   ├── Examples:
│   │   ├── SSL / TLS
│   │   ├── JPEG, MPEG
│   │   └── ASCII, EBCDIC conversions
│   │
│   └── Data Form: **Data**
│
└── Layer 7: Application Layer
    │
    ├── Simple Definition:
    │   Provides services and interfaces for end users and applications.
    │
    ├── Functions:
    │   ├── User interaction with the network
    │   ├── Application access to network services
    │   └── Resource sharing and email, file, web services
    │
    ├── Protocols:
    │   ├── HTTP / HTTPS (Web)
    │   ├── FTP / SFTP (File Transfer)
    │   ├── SMTP / POP3 / IMAP (Email)
    │   ├── DNS (Domain Name System)
    │   └── SNMP (Network Management)
    │
    └── Data Form: **Data**
