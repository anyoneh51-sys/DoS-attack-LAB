# DoS-attack-LAB
the TCP SYN Flood
• Executive Summary: A clear introduction defining the scope of the TCP SYN Flood Denial of Service (DoS) attack.
• Detailed Lab Environment: Explains the isolated architecture without revealing your private lab IPs.
• Complete Technical Metrics Table: Features all your exact data points (Port 0 kernel drops, Port 80 background processing, and Port 80 application exhaustion up to 90% CPU and 5% Disk IOPS).
• Deep-Dive Root Cause Analysis: Explains the system behavior behind the numbers—specifically contrasting network layer packet drops with application layer thread-pool queuing and server logging overhead.
• Mitigation Strategies: Provides professional recommendations such as implementing SYN Cookies, per-IP rate-limiting, and stateful perimeter firewalls to complete your security portfolio case study.
