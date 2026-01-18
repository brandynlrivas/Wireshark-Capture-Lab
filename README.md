📡 Wireshark Capture & Protocol Analysis Lab
📝 Overview
This project captures and analyzes live network traffic using Wireshark on Windows 11
The goal was to capture key network protocols and demonstrate packet analysis using Wireshark display filters.

📦 Traffic Types Captured
ICMP — Captured via ping google.com
DNS — Captured via nslookup openai.com
TCP 3-Way Handshake — Captured via a fresh web connection
TCP Port 80 Traffic (HTTP-related) — Captured via unsecured connection
📸 Screenshots
1. ICMP (Ping Traffic)
Captured Echo Request and Echo Reply packets.

ICMP Traffic

2. DNS (Domain Name System Lookup)
Captured DNS query and response during nslookup.

DNS Traffic

3. TCP 3-Way Handshake
Captured the SYN → SYN-ACK → ACK sequence during a connection setup.

TCP Handshake

4. TCP Port 80 Traffic (HTTP Attempt)
Captured TCP packets directed to Port 80 (HTTP protocol port), even though direct HTTP traffic was force-upgraded to HTTPS.

TCP Port 80 Traffic

5. Random Traffic Snapshot (Extra)
Captured miscellaneous background traffic.

Random Traffic

📂 Project Structure
🧠 Skills Practiced
Packet capturing and saving
Applying Wireshark filters
Analyzing ICMP, DNS, TCP handshakes, and HTTP-related traffic
Documenting findings with screenshots
Real-world troubleshooting with HTTPS-only environments

