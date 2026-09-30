---
type: "Campaign"
source: MITRE ATT&CK
id: "C0062"
source_url: "https://attack.mitre.org/campaigns/C0062"
created: "2026-04-20"
modified: "2026-07-31"
---
# C0062: Anthropic AI-orchestrated Campaign

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Campaign  
**ATT&CK ID:** C0062  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

The [Anthropic AI-orchestrated Campaign](https://attack.mitre.org/campaigns/C0062) was conducted in September 2025 by a likely China nexus espionage actor identified as GTG-1002. The [Anthropic AI-orchestrated Campaign](https://attack.mitre.org/campaigns/C0062) was a highly coordinated operation that manipulated Claude Code to perform reconnaissance, vulnerability discovery, exploitation, lateral movement, credential harvesting, data analysis, and exfiltration operations at approximately 30 entities in the technology, financial, chemical, and government sectors. During the [Anthropic AI-orchestrated Campaign](https://attack.mitre.org/campaigns/C0062), human operators used Claude Code agents and Model Context Protocol (MCP) tools to automate cyber operations. Operators broke attacks into discrete tasks, used crafted prompts, and established personas to bypass AI guardrails, enabling the agents to execute the operations with minimal human involvement.(Citation: Anthropic AI Orchestrated Campaign NOV 2025)(Citation: Anthropic Disrupting AI Espionage NOV 2025)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: C0062](https://attack.mitre.org/campaigns/C0062)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
