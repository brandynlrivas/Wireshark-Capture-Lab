# 📡 Wireshark Capture & Protocol Analysis Lab

## 📝 Overview
This project captures and analyzes **live network traffic** using **Wireshark on Windows 11**. The goal is to capture key network protocols and demonstrate packet-level analysis using Wireshark display filters in both secured (HTTPS) and unsecured (HTTP) environments.

## 🖥 Environment
- Operating System: Windows 11  
- Tool: Wireshark  
- Network: Active internet connection  
- Traffic Generation: Command Prompt and Web Browser  

## 📦 Traffic Types Captured
The following traffic types were intentionally generated and captured:
- **ICMP** — Captured via `ping google.com`
- **DNS** — Captured via `nslookup openai.com`
- **TCP 3-Way Handshake** — Captured by initiating a fresh web connection
- **HTTP Traffic (Port 80)** — Successfully captured in plaintext from an unsecured website

## 📸 Screenshots
### 1. ICMP (Ping Traffic)
Captured ICMP Echo Request and Echo Reply packets, confirming basic network connectivity.
<img width="891" height="686" alt="ICMP (Ping Traffic)" src="https://github.com/user-attachments/assets/e4b915a6-5126-4c27-bf9c-bc959aa1c7dd" />

### 2. DNS (Domain Name System Lookup)
Captured DNS query and response packets during `nslookup openai.com`, demonstrating domain name resolution.
<img width="891" height="686" alt="DNS" src="https://github.com/user-attachments/assets/44d7c3ac-0e66-4df7-977d-4c231d92a0d2" />

### 3. TCP 3-Way Handshake
Captured the SYN → SYN-ACK → ACK sequence during a new TCP connection setup, confirming successful session establishment.
<img width="891" height="686" alt="TCP 3 Way Handshake" src="https://github.com/user-attachments/assets/9742a977-ebd9-4d0f-873a-55f0deda9eb6" />

### 4. HTTP Traffic (Unsecured Website)
Captured plaintext HTTP traffic from an unsecured website over TCP port 80. HTTP request and response headers, including GET requests, were visible and analyzed.
<img width="891" height="686" alt="TCP Port 80 Traffic" src="https://github.com/user-attachments/assets/6572b611-b0b0-4c71-b1da-005be7882cbd" />

### 5. Creating Wireshark Filter Buttons
Wireshark allows frequently used display filters to be saved as filter buttons for quick access during analysis.
<img width="891" height="686" alt="Creating HTTPS Filter" src="https://github.com/user-attachments/assets/e78a69be-dc70-48da-922e-78db84329a91" />


## 🧠 Skills Practiced
- Packet capturing and saving on Windows 11  
- Applying and managing Wireshark display filters  
- Creating reusable Wireshark filter buttons  
- Analyzing ICMP, DNS, TCP handshakes, and HTTP traffic  
- Documenting findings with screenshots  
- Real-world troubleshooting in both HTTP and HTTPS environments  

## 🛡 Notes
This lab successfully captured unencrypted HTTP traffic from an unsecured website, allowing full inspection of HTTP requests and responses. This demonstrates the security risks of plaintext communication and highlights the importance of HTTPS in modern networks.



