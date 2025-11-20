# Wireshark Network Analysis Practical (ICT414)

## Overview
This repository contains the practical submission for the ICT414 Wireshark Network Analysis. The objective was to capture live network traffic using Wireshark and analyze an HTTP request made to the website www.rocktv.app.

## Steps Performed
1. Started Wireshark and selected the active network interface.
2. Captured live network traffic for 1–2 minutes.
3. Visited https://www.rocktv.app during the capture.
4. Applied Wireshark filters:
   ```
   http
   tcp.port == 443
   ip.addr == <my_ip>
   ```
5. Identified one HTTP GET request and extracted:
   - Client IP address 
   - Server IP address
   - URL requested
   - HTTP response code
   - Whether the request was successful
6. Took a screenshot of filtered HTTP packets.
7. Saved the capture file as ict414_capture.pcapng.

## Repository Contents
- report_<IssacKhumbirai>.pdf — Full analysis report  
- ict414_capture.pcapng — Packet capture file  
- README.md — Documentation  

## Bonus Included
- Packet size comparison  
- HTTP method identification (GET)

