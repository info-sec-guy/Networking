# Network Security


## Anatomy of a Byte
- A single 1 or 0 is a bit `1` 
- Eight 1s or 0s are called a byte `01000001`
- Four bits is a nibble `0000`

| High bit  |   |   |   |   |   |   | Low bit  |
|---|---|---|---|---|---|---|---|
| 128  |  64 | 32  | 16  | 8  | 4  | 2  | 1  |


## Conversions 

Decimal Digits: `0-9`

Binary: `0-1`

Hex: `0-9` and `A-F`

|    |     |   
|--- |-----|
| A  | 10  |   
| B  | 11  |  
| C  | 12  |  
| D  | 13  |   
| E  | 14  |  
| F  | 15  |  

## IP Calculator:
* [ipcalc](http://jodies.de/ipcalc) takes an IP address and netmask and calculates the resulting broadcast, network, Cisco wildcard mask, and host range.

## Common Network Hardware
Network Interface Card (NIC):
* Installed in each PC, server, and device
* Connects the computer to the network

Switch:
* Forwards traffic to destination hardware address
* Connects PCs, servers, and so on together

Router:
* Forwards traffic to its destination IP address
* Connects switches together

## The OSI Model (Stack)
Application: Network process to application
  * DNS
  * WWW/HTTP
  * EMAIL/POP
  * SMTP
  * Telnet
  * FTP
  
Presentation: Data representation and encryption
  * HTML
  * DOC
  * JPEG
  * MP3

Session: Interhost communication

Transport: End-to-end connections and reliability
  * TCP
  * UDP
  * SSL/TLS

Network: Path determination and logical addressing
  * IP
  * ARP
  * IPsec
  * ICMP
  * OSPF

Data Link: Physical addressing
  * MAC

Physical: Media, signal, and binary transmission

## IPv4 Header
**IP Version, 4 Bits:** Determines the version of the IP protocol

**Protocol, 8 Bits:** Identifies the encapsulated protocol

**Time To Live (TTL), 8 Bits:** Number of hops a packet is allowed to take before it reaches its destination

**Fragmentation, 16 Bits (13 Bits Fragment Offset and 3 Bits for Flags):** Used to fragment the packet or break it up into smaller individual packets

**Source Address and Destination Address, 32 Bits Each:** Source and destination systems 


## IPv4 vs. IPv6

|  IPv4                                 | IPv6                                |   
|------------------------------------- |--------------------------------------|
| 32-bit address                       | 128-bit address                      |   
| No Authentication                    | Provides authentication of endpoints |  
| Encryption provided by applications  | Support for encryption in protocol   |  
 
