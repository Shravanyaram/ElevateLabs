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

#### Protocol 2: DNS
- **Purpose**: Domain name resolution
- **Characteristics**: Query/response, typically UDP port 53
- **Observations**: [Add your specific observations]

#### Protocol 3: TCP
- **Purpose**: Reliable connection-oriented communication
- **Characteristics**: Three-way handshake, sequence numbers

### Step 7: Export Capture File
- Exported the complete capture as a `.pcap` file
- File saved as: `network_capture_analysis.pcap`
- Verified file integrity and accessibility


### Notable Observations
- [Add specific observations about packet sizes, frequencies, etc.]
- [Note any interesting traffic patterns]
- [Mention any security-related observations]

## Deliverables
1. ✅ **network_capture_analysis.pcap** - Complete packet capture file
2. ✅ **README.md** - This detailed report documenting the analysis process
3. ✅ **Screenshots** - Key Wireshark interface screenshots showing different protocols

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
├── task5_capture.pcap
├── screenshots/
│   ├── screenshot of the capture.png
│   ├── screenshot of capture.png
└── analysis_notes.txt
```

## Conclusion
This task provided hands-on experience with network packet analysis, enhancing understanding of network protocols and traffic patterns. The analysis revealed [add your conclusions about what you learned].

