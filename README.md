# Cybersecurity Incident Report: Network Traffic Analysis

## Part 1: Provide a summary of the problem found in the DNS and ICMP traffic log

The network protocol analyzer logs reveal that port 443 is unreachable when trying to access the secure employee background check website. Since port 443 is typically used for HTTPS traffic, this could point to an issue with the web server or firewall configuration. Alternatively, it might be a sign of a potential malicious attack targeting the web server.

## Part 2: Explain your analysis of the data and provide at least one cause of the incident

The incident occurred earlier this morning when the Human Resources (HR) team reported being unable to access the background check web portal. In response, the network security team began running tests using the tcpdump network protocol analyzer tool. The logs showed that port 443, which handles HTTPS traffic, is unreachable. We are continuing to investigate the issue to identify the root cause and restore access to the secure web portal. Our next steps involve checking the firewall configuration to ensure port 443 is not blocked and reaching out to the system administrator to inspect the web server for any signs of an attack. The HR team suspects that a recent new hire may be attempting to prevent the background check from being conducted, while the network security team believes this individual could have launched an attack to disrupt the website.
