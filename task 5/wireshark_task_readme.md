# Task 5: Capture and Analyze Network Traffic Using Wireshark

## Objective
Capture live network packets and identify basic protocols and traffic types using Wireshark.

## Tools Used
- **Wireshark** (free network protocol analyzer)

## Task Overview
This task involves capturing network traffic, analyzing different protocols, and understanding packet structures to develop hands-on packet analysis skills and protocol awareness.

## Step-by-Step Implementation

### Step 1: Install Wireshark
- Downloaded and installed Wireshark from the official website
- Verified installation and launched the application
- Confirmed network interface detection

### Step 2: Start Network Capture
- Identified active network interface (e.g., Wi-Fi, Ethernet)
- Started packet capture on the selected interface
- Verified capture was recording incoming/outgoing traffic

### Step 3: Generate Network Traffic
- Browsed multiple websites to generate HTTP/HTTPS traffic
- Performed ping commands to generate ICMP traffic
- Accessed different services to create diverse protocol traffic
- Examples of traffic generated:
  - Web browsing (HTTP/HTTPS)
  - DNS lookups
  - Ping commands (ICMP)
  - Other application traffic

### Step 4: Stop Capture
- Allowed capture to run for approximately 1 minute
- Stopped the capture session
- Reviewed total packets captured

### Step 5: Apply Protocol Filters
Applied various filters to analyze different protocols:
- **HTTP Filter**: `http` - to view web traffic
- **DNS Filter**: `dns` - to view domain name queries
- **TCP Filter**: `tcp` - to view TCP connections
- **UDP Filter**: `udp` - to view UDP traffic
- **ICMP Filter**: `icmp` - to view ping responses

### Step 6: Protocol Identification
Identified and analyzed at least 3 different protocols:

#### Protocol 1: HTTP
- **Purpose**: Web traffic communication
- **Characteristics**: Request/response based, port 80
- **Observations**: [Add your specific observations]

#### Protocol 2: DNS
- **Purpose**: Domain name resolution
- **Characteristics**: Query/response, typically UDP port 53
- **Observations**: [Add your specific observations]

#### Protocol 3: TCP
- **Purpose**: Reliable connection-oriented communication
- **Characteristics**: Three-way handshake, sequence numbers
- **Observations**: [Add your specific observations]

### Step 7: Export Capture File
- Exported the complete capture as a `.pcap` file
- File saved as: `network_capture_analysis.pcap`
- Verified file integrity and accessibility

## Key Findings Summary

### Traffic Analysis Results
- **Total Packets Captured**: [Insert number]
- **Capture Duration**: ~1 minute
- **Primary Protocols Observed**: HTTP, DNS, TCP, UDP, ICMP
- **Most Active Protocol**: [Insert findings]

### Protocol Distribution
- HTTP/HTTPS: [percentage/count]
- DNS: [percentage/count]
- TCP: [percentage/count]
- UDP: [percentage/count]
- Other: [percentage/count]

### Notable Observations
- [Add specific observations about packet sizes, frequencies, etc.]
- [Note any interesting traffic patterns]
- [Mention any security-related observations]

## Deliverables
1. ✅ **network_capture_analysis.pcap** - Complete packet capture file
2. ✅ **README.md** - This detailed report documenting the analysis process
3. ✅ **Screenshots** - Key Wireshark interface screenshots showing different protocols

## Interview Questions Preparation

### 1. What is Wireshark used for?
Wireshark is a network protocol analyzer used for network troubleshooting, analysis, software and communications protocol development, and education.

### 2. What is a packet?
A packet is a formatted unit of data carried by a packet-switched network, containing both payload data and routing information.

### 3. How to filter packets in Wireshark?
Use display filters in the filter bar (e.g., `http`, `dns`, `tcp.port == 80`) or capture filters before starting capture.

### 4. What is the difference between TCP and UDP?
- **TCP**: Connection-oriented, reliable, ensures packet delivery and order
- **UDP**: Connectionless, faster, no delivery guarantee

### 5. What is a DNS query packet?
A DNS query packet contains a request to resolve a domain name to an IP address, typically sent to port 53.

### 6. How can packet capture help in troubleshooting?
Packet capture helps identify network issues, analyze traffic patterns, detect security threats, and understand application behavior.

### 7. What is a protocol?
A protocol is a set of rules and standards that define how data is transmitted and received over a network.

### 8. Can Wireshark decrypt encrypted traffic?
Wireshark can only decrypt encrypted traffic if you have the decryption keys; otherwise, it shows encrypted payload data.

## Key Concepts Learned
- ✅ Packet capture techniques
- ✅ Protocol analysis methodology
- ✅ TCP/IP stack understanding
- ✅ Network troubleshooting approaches
- ✅ Traffic filtering and analysis

## Files in Repository
```
wireshark-network-analysis/
├── README.md
├── network_capture_analysis.pcap
├── screenshots/
│   ├── wireshark_interface.png
│   ├── http_filter.png
│   ├── dns_analysis.png
│   └── protocol_hierarchy.png
└── analysis_notes.txt
```

## Conclusion
This task provided hands-on experience with network packet analysis, enhancing understanding of network protocols and traffic patterns. The analysis revealed [add your conclusions about what you learned].

## Tools and Environment
- **Operating System**: [Your OS]
- **Wireshark Version**: [Version number]
- **Network Interface**: [Interface used]
- **Analysis Date**: [Date completed]

---
*Task completed as part of Cyber Security Internship - Task 5*