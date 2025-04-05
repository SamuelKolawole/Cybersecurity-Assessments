# Cybersecurity Incident Report

## Assignment Overview
This report is part of an assignment to analyze DNS and ICMP traffic logs related to access issues on the website www.yummyrecipesforme.com. The task involved investigating why users were unable to access the website, identifying potential causes, and providing recommendations for resolution.

## Assignment Questions
1. Analyze the DNS and ICMP traffic logs to identify the issue causing the access problem to www.yummyrecipesforme.com.
2. Provide an explanation of the data analysis, including potential causes of the issue.
3. Suggest next steps for troubleshooting and resolution.

---

## Part 1: Problem Found in DNS and ICMP Traffic Log

The network protocol analyzer logs indicate that when attempting to access the website [www.yummyrecipesforme.com](http://www.yummyrecipesforme.com), users received the error message "destination port unreachable." The logs show that UDP packets were sent to the DNS server at IP address 203.0.113.2 on port 53 to resolve the domain name, but the DNS server responded with an ICMP error message stating "udp port 53 unreachable." This indicates that the DNS service was unavailable, preventing users from retrieving the IP address needed to access the website.

## Part 2: Analysis and Cause of the Incident

The incident was reported by several customers who were unable to access the client company’s website. After verifying the issue by attempting to visit the site and receiving the same error, a network analysis was conducted using tcpdump. The captured logs confirmed that DNS queries sent via UDP to port 53 were met with ICMP responses indicating that the port was unreachable.

One possible cause of this issue is that the DNS server at 203.0.113.2 may have been down or misconfigured, preventing it from responding to queries. Another potential explanation is that a firewall or security configuration change may have blocked access to port 53, causing DNS resolution to fail. Further investigation is necessary to determine if this was due to a service outage, a misconfiguration, or a possible cyber attack targeting the DNS service. Next steps include contacting the DNS server administrator to verify its status and checking firewall rules to see if they have been updated or improperly set.
