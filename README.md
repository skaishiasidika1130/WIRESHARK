# WIRESHARK
To perform live packet capture using Wireshark, analyze different network protocols, and summarize findings for network troubleshooting and monitoring.
Wireshark-Network-Capture-Task
I have done a Network Capture using Wireshark. this is my report on it. and gained Hands-on packet analysis skils and protocol awareness.

🧠 Wireshark Network Capture and Analysis (Windows)
🎯 Objective
To perform live packet capture using Wireshark, analyze different network protocols, and summarize findings for network troubleshooting and monitoring.

⚙️ Steps Performed
1. Install Wireshark
Download Wireshark from https://www.wireshark.org/download.html
Install it along with Npcap (required for packet capture).
2. Start Capturing on Your Active Network Interface
Open Wireshark.
Select your active network interface (Wi-Fi or Ethernet) that shows live traffic.
Click the blue shark fin (▶️) icon to begin capturing packets.
3. Browse a Website or Ping a Server to Generate Traffic
Visit websites like https://www.google.com or https://www.wikipedia.org
Or open Command Prompt and run:
ping google.com
This generates traffic for DNS, TCP, ICMP, and HTTP/HTTPS protocols.

4. Stop Capture After a Minute
Click the red square stop button (⏹️) on the toolbar to stop capturing.
You can now analyze the captured packets.
5. Filter Captured Packets by Protocol
Use Wireshark’s Display Filter bar to show specific traffic.

Protocol	Filter Command
HTTP	http
DNS	dns
TCP	tcp
ICMP	icmp
Type the filter and press Enter to view only that protocol’s packets.

6. Identify at Least 3 Different Protocols
During the capture, you should observe multiple protocols such as:

DNS – Domain name queries and responses
TCP/UDP – Data transmission
HTTP/HTTPS – Web communication
ICMP – Ping packets (if you used ping)
7. Export the Capture as a .pcap File
Go to File → Save As...
Save the capture as network_capture.pcap
8. Summarize Findings and Packet Details
Summary Example: During the Wireshark capture, several protocols were detected including DNS, TCP, and HTTP traffic.

DNS packets resolved domain names like google.com.
TCP packets established connections and transferred data.
HTTP packets showed website requests and responses.
The capture confirmed normal browsing behavior with successful communication between client and servers.
Total Packets Captured: ~1000
Active Protocols: DNS, TCP, HTTP, ICMP
Capture File: network_capture.pcap


📋 Summary Table
Step	Action	Output
1	Install Wireshark	Application installed successfully
2	Start Capture	Live packets displayed
3	Generate Traffic	Packets captured during browsing/ping
4	Stop Capture	Capture saved for analysis
5	Apply Filters	Displayed specific protocol traffic
6	Identify Protocols	Found DNS, TCP, HTTP
7	Export File	.pcap file saved
8	Summary	Documented findings

<img width="1054" height="513" alt="Screenshot 2025-10-29 084827" src="https://github.com/user-attachments/assets/11b45682-3c4e-4e98-b832-484321f4f67b" />
<img width="1046" height="591" alt="Screenshot 2025-10-29 084800" src="https://github.com/user-attachments/assets/5b018786-4ce1-4e18-a04b-6993a795dbe0" />
<img width="1047" height="590" alt="Screenshot 2025-10-29 084752" src="https://github.com/user-attachments/assets/015f0a4d-5010-4c86-95ab-aa0826119ea4" />
<img width="1045" height="588" alt="Screenshot 2025-10-29 084745" src="https://github.com/user-attachments/assets/de49d146-62cb-4cb3-9334-cf391944c745" />
<img width="1044" height="587" alt="Screenshot 2025-10-29 084735" src="https://github.com/user-attachments/assets/492db953-f042-47ba-a595-253403f2e2fd" />
<img width="1044" height="586" alt="Screenshot 2025-10-29 084727" src="https://github.com/user-attachments/assets/87125589-1f48-4ad3-ab7c-304d50eb4a6b" />
<img width="1051" height="589" alt="Screenshot 2025-10-29 084718" src="https://github.com/user-attachments/assets/9c8f69f0-73dc-4691-9395-804485f8359c" />
<img width="1045" height="589" alt="Screenshot 2025-10-29 084710" src="https://github.com/user-attachments/assets/564fffc1-9f05-4f94-bd36-f4aadb44b99d" />

✅ Author
Name: SK AISHIA SIDIKA
Task: Internship Task – Wireshark Network Capture
Platform: Windows
Date: October 2025 Screenshot 2025-10-29 105633 Screenshot 2025-10-29 105644 Screenshot 2025-10-29 110004

<img width="1047" height="587" alt="Screenshot 2025-10-29 084950" src="https://github.com/user-attachments/assets/3f5ff6b6-0daa-4c57-a54b-e844aab27463" />
<img width="1046" height="593" alt="Screenshot 2025-10-29 084942" src="https://github.com/user-attachments/assets/71b7e712-786a-4c1b-8a04-82d8918f8d60" />
<img width="1046" height="589" alt="Screenshot 2025-10-29 084933" src="https://github.com/user-attachments/assets/84ca4a14-44f3-43f1-81d5-be0e1568b8e1" />



