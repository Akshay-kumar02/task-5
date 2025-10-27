# task-5
1.Install Wireshark
Download and install from https://www.wireshark.org/download.html
.

2.Start Capturing

Open Wireshark.

Select your active network interface (Wi-Fi or Ethernet).

3.Click Start Capturing Packets.

Generate Network Traffic

4.Browse any website or run:

ping google.com


5.Stop Capture

Let it run for about 1 minute.

6.Click the red Stop button.

Filter Packets by Protocol
Use the filter bar in Wireshark:

http → HTTP traffic

dns → DNS lookups

tcp → TCP packets

icmp → Ping packets

7.Identify Protocols
You should see at least 3 different protocols, such as:

DNS

HTTP

TCP

ICMP

8.Export Capture

Go to File → Export Specified Packets...

9.Save as network_capture.pcap.

10.Summary of Findings
Example summary:

DNS: Resolves domain names (e.g., google.com)

HTTP: Web browsing traffic

TCP: Connection setup and data transfer

ICMP: Ping requests and replies

11.Files

network_capture.pcap – Captured packets

README.md – Instructions and summary

Tools Used

Wireshark

Web browser / Ping command

Windows, macOS, or Linux
