# Suspicious Traffic Investigation

## Objective
The purpose of this project was to identify abnormal or unusual behavior while analyzing TCP traffic in Wireshark.

## Tools Used
- Wireshark

## What I Did
- Captured live network traffic using Wireshark
- Applied TCP analysis filters to identify retransmissions and failed connections
- Generated network activity by browsing websites and attempting connections to invalid domains
- Reviewed packet details including source IPs, destination IPs, and TCP errors

## Findings
- Observed multiple TCP retransmission packets during traffic analysis
- Identified interrupted or delayed network communication between devices and external servers
- Determined that the abnormal traffic appeared to be related to failed connection attempts rather than malicious activity

## What I Learned
- TCP retransmissions can occur during unstable or interrupted network communication
- Not all abnormal traffic is malicious
- Wireshark can be used to investigate unusual traffic patterns and connection issues
