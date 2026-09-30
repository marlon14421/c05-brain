---
type: "Data Component"
source: MITRE ATT&CK
id: "DC0104"
source_url: "https://attack.mitre.org/datacomponents/DC0104"
created: "2021-10-20"
modified: "2025-11-12"
---
# DC0104: Response Content

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Data Component  
**ATT&CK ID:** DC0104  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

Captured network traffic that provides details about responses received during an internet scan. This data includes both protocol header values (e.g., HTTP status codes, IP headers, or DNS response codes) and response body content (e.g., HTML, JSON, or raw data). Examples: - HTTP Scan: A web server responds to a probe with an HTTP 200 status code and an HTML body indicating the default page is accessible. - DNS Scan: A DNS server replies to a query with a resolved IP address for a domain, along with details like Time-To-Live (TTL) and authoritative information. - TCP Banner Grab: A service listening on a port (e.g., SSH or FTP) responds with a banner containing service name, version, or other metadata.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: DC0104](https://attack.mitre.org/datacomponents/DC0104)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
