This test is without Makefile. Steps in test:
1. Designer could add some configurations in json file and not necessary to change something in the code. 
2. From wireshark I recorded traffic and saved in pcap file. Further pcap_reader.py make raw ethenet packets and sent RGMII to test.
Description to files:
json_reader.py - pasre json file from designer
pcap_reader.py - make raw packets in txt from pcap file
test.py - Cocotb test
