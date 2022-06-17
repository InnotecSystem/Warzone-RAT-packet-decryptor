# Warzone-RAT-packet-decryptor
Warzone RAT packet decryptor is a tool to detect and decrypt malicious packets related to Warzone RAT malware from a PCAP file. This application can track all the activity performed by the malicious actor, showing the content of the packets exchanged between the C2 and the infected user.

# Installation
To use the script it is necessary to install the Scapy and Chepy libraries.
```python
pip install scapy
```
```python
pip install chepy
```

# Usage
To use it, just enter the path to your PCAP in line 161 of the code. Once you execute the script, you will have to set up the local port used by the malware.

