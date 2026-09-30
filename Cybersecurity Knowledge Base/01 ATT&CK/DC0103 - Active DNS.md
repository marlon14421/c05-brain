---
type: "Data Component"
source: MITRE ATT&CK
id: "DC0103"
source_url: "https://attack.mitre.org/datacomponents/DC0103"
created: "2021-10-20"
modified: "2025-10-21"
---
# DC0103: Active DNS

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Data Component  
**ATT&CK ID:** DC0103  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

"Domain Name: Active DNS" data component captures queried DNS registry data that highlights current domain-to-IP address resolutions. This data includes both direct queries to DNS servers and records that provide mappings between domain names and associated IP addresses. It serves as a critical resource for tracking active infrastructure and understanding the network footprint of an organization or adversary. Examples: - DNS Query Example: `nslookup example.com`, `dig example.com A` - PTR Record Example: `dig -x 192.168.1.1` - Tracking Malicious Domains: DNS logs reveal repeated queries to suspicious domains like malicious-site.com. The IPs resolved by these domains may be indicators of compromise (IOCs). - DNS Record Types - A/AAAA Record: Maps domain names to IP addresses (IPv4/IPv6). - CNAME Record: Canonical name records, often used for redirects. - MX Record: Mail exchange records, used to route emails. - TXT Record: Can include security information like SPF or DKIM policies. - SOA Record: Start of authority record for domain management. - NS Record: Lists authoritative name servers for the domain. This data component can be collected through the following measures: - System Utilities: Use built-in tools like `nslookup`, `dig`, or host on Linux, macOS, and Windows to perform active DNS queries. - DNS Logging - Windows DNS Server: Enable DNS Analytical Logging to capture DNS queries and responses. - Bind DNS: Enable query logging in the named.conf file. - Cloud Provider DNS Logging - AWS Route 53: Enable query logging through CloudWatch or S3: - Google Cloud DNS: Enable logging for Cloud DNS queries through Google Cloud Logging. - Network Traffic Monitoring: Use tools like Wireshark or Zeek to analyze DNS queries within network traffic. - Security Information and Event Management (SIEM) Integration: Aggregate DNS logs in a SIEM like Splunk to create alerts and monitor patterns. - Public OSINT Tools: Use OSINT platforms like VirusTotal, or PassiveTotal to collect information on domains and their associated IP addresses.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: DC0103](https://attack.mitre.org/datacomponents/DC0103)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
