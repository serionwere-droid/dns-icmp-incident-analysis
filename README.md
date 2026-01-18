Cybersecurity Incident Report: 
Network Traffic Analysis

Part 1: Provide a summary of the problem found in the DNS and ICMP 
traffic log.

The UDP protocol reveals that: indicating that the UDP packet was undeliverable to port 53 of the DNS server 


The port noted in the error message is used for: is the standard network port used by the Domain Name System (DNS) to translate human-readable domain names (like google.com) into machine-readable IP addresses, which is port 53 DNS port.

The most likely issue is: the DNS service failure or  misconfiguration of DNS  server.



Part 2: Explain your analysis of the data and provide at least one cause of the incident.
Time incident occurred: 1:24 p.m

Explain how the IT team became aware of the incident: Several customers of clients reported that they were not able to access the client company website www.yummyrecipesforme.com, and destination port unreachable after waiting for the page to load. 

Explain the actions taken by the IT department to investigate the incident: They start, by attempt to visit the website and  also receive the destination port unreachable. They had to trouble shoot their system by starting the tcpdump to analyze the network to figure out  the cause of the problem


Note a likely cause of the incident: it was likely caused by server misconfiguration , the rules set in  the firewall they had to check in order to determine if it was the prolem causing the destination to be unreacheable.


