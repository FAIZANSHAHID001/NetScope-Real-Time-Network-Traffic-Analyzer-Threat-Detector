Features:

**Live traffic capture with tcpdump

Packet parsing using Scapy

Visualization with Matplotlib

Threat detection via custom rules

Automated PDF reporting**

Tech Stack: Python · Scapy · tcpdump · Matplotlib · Pandas · FPDF

Run Locally:

sudo tcpdump -i en0 -w traffic.pcap -c 500
python3 netscope.py
python3 threatscan.py
python3 netscope_report.py
