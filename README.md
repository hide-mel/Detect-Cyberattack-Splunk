# Detect-Cyberattack-Splunk
 
# Project: Detecting cyberattacks in network traffic data

# Overview

In this project, I am given a network traffic dataset and use Splunk to identify cyberattacks by leveraging the analytics capabilities of this software. The aim is to strengthen my skills in analysing traffic patterns and identifying their changes over time, which might be signs of suspicious activities. In searching the evidence of cyberattacks, and hunting the attack sources and targets, I will develop the practical security incident investigation skills and mindset of a real-world Cyber Security Analyst. In addition, I will skill-up myself in tracing attacks back in time to create an attack narrative1. Then generating and extracting significant patterns/features of detected attacks will pave the way for the next project that is heavily machine learning focused. Lastly, I will develop my skills as a Cyber Defender by proposing the countermeasures to detect/mitigate similar attacks in the future.
I will write a technical report on my findings, and my proposal on how the identified attack patterns and evidence can be used to detect and mitigate similar cyberattacks in future.

# Deliverables
A technical report that describes my methodology for
1. Ingesting the given pcap file into Splunk 
2. Analyzing the data using Splunk, validating the evidences of the following attack scenarios contained in the given pcap file. I can use either Splunk Search or PCAP Analyzer Dashboard where applicable, new field extraction may be required if I are using Splunk Search.
2.1 SPAM.
a. Calculate how many email addresses have been targeted by this spam 
b. List the start time and the end time, the first and last recipient (email address) of
this email spam 
2.2 Port scan. TCP SYN scan is one of the most common technique for port scan. Identify the TCP SYN scan activities of 249.56.230.66 in the given dataset,
including:
a. The statistics of packets sent each minute
b. The number of hosts that were scanned
c. The start time and the end time
2.3 HTTP.
a. Identify all the URI strings related to the malware downloaded from
“my.shopandbuy.com” and “chiashop.net” 
3. Evaluating the consequences of the attacks on the targeted network 
4. Generating and extracting the significant patterns/features for attack scenarios above, e.g.,
“src_IP+src_Port” can be a significant pattern to detect Flooding DDoS attacks 
5. Assuming I am the Cybersecurity Analyst who is part of the Incident Response team, and I’ve been given the greenlight to put in any controls to mitigate this attack. I can safely ignore any business impact as the priority is to the contain the current attack.

Technical Report
A technical report of no more than 2500 words in PDF format, comprising:
1. A data description and a summary of detected attacks, including the IP addresses of attackers and victims, the attacked services, the timestamp, and the type of the attack per attack scenario.
2. Methodology of analysis to find evidence of cyberattacks in the network traffic data.
3. Description of each attack and the attack narrative.
4. Possible approaches for extracting features (fields) and summary of my approach.
5. Proposed countermeasures per attack scenarios.
6. Conclusions
