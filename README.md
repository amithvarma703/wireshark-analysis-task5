# 🐬 wireshark-analysis-task5

Wireshark capture and protocol analysis.

## 🎯 Objective
Capture live network traffic, filter by protocol, and identify basic protocols and traffic types.

## 🛠 Tools Used
- Wireshark (free and open-source)

## ✅ Steps Performed
1. Installed Wireshark.
2. Started capturing on the active network interface.
3. Generated traffic by browsing websites and running `ping google.com`.
4. Stopped the capture after ~1 minute.
5. Filtered packets by protocol:
   - Used `http` filter for HTTP traffic
   - Used `dns` filter for DNS queries and responses
   - Used `icmp` filter for ping packets
6. Identified at least three protocols: HTTP, DNS, and ICMP.
7. Exported the capture as a `.pcap` file.

## 📊 Findings
| Protocol | Purpose                        | Observations                                          |
|--------:|---------------------------------|------------------------------------------------------|
| HTTP     | Web browsing                   | HTTP GET/POST requests and server responses           |
| DNS      | Resolving domain names         | DNS queries to resolve website names                  |
| ICMP     | Network diagnostics (ping)     | Echo requests and replies showing round-trip times    |

## 📂 Deliverables
- Packet capture file: `network_traffic_capture.pcap`
- This `README.md` file with summary and analysis

## 📝 Summary
This task helped build hands-on skills in:
- Using Wireshark to capture and filter traffic
- Recognizing common network protocols
- Understanding how everyday network activity looks at the packet level

