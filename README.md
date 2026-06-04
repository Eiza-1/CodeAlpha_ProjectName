# CodeAlpha_ProjectName
Python program for capturing and analyzing network traffic packets.
# Network Traffic Analyzer - README

**Version:** 1.0
**Last Updated:** May 5th, 2026
**Author:** [Anthony Ndidi Mbagwu/ eiza-1]
**Website:** https://guns.lol/eiza

---

## Overview

The Network Traffic Analyzer is a tool designed to capture, analyze, and visualize network traffic. It provides a comprehensive view of network activity, helping to identify potential issues, security threats, and optimize network performance.

## Installation

**Prerequisites:**

*   Operating System: Windows 10/11, Linux (Ubuntu 20.04+), macOS
*   Required Software: Python 3.8+, libpcap/WinPcap, Qt5, scapy

**Installation Steps:**

1.  Download the appropriate package for your operating system from [Link to Download].
2.  Extract the archive to your desired location.
3.  “Run `python sniffer.py install`”

## Usage

**Basic Command-Line Usage:**

The analyzer is primarily controlled via the command line.

* select either the scapy(which is recommended) or raw socket for your analysis

**Example of filters you can use:**

* 'tcp' - Only TCP packets
* 'udp' - Only UDP packets
* 'host 8.8.8.8' - Packets to/from 8.8.8.8
* 'port 80' - Packets on port 80

## Configuration

*   **Configure which filter you want to analyze e.g tcp** 
    *   **Enter number of packets to capture (0 for infinite)** and your done
                     A strip of analysis output is generated!!
    *   [2026-06-04 21:03:47] Packet #2
    *   Ethernet: 14:13:33:de:65:53 -> 01:00:5e:7f:ff:fa
    *   IP: 192.168.100.8 -> 239.255.255.250 (TTL: 1)
    *   Protocol: UDP (17)
    *   Transport: UDP: 54559 -> 1900
    *   Payload (170 bytes): b'M-SEARCH * HTTP/1.1\r\nHOST: 239.255.255.250:1900\r\nM'...
 
    *                      Feel free to use this command for the end process when you're done!! (Press Ctrl+C to stop)

## Troubleshooting

*   **No Traffic Captured:**
    *   Verify the network interface is enabled and accessible.
    *   Ensure the analyzer has the necessary permissions to capture traffic (root/administrator privileges may be required).
*   **Performance Issues:**
    *   Close other applications consuming network resources.

## Support & Contact

*   **Bug Reports & Feature Requests:**
*   **General Support:** ndidithegreat@gmail.com

---

**License:** [MIT License]

**Copyright © [2026] [eiza-1 /Code Alpha]**
