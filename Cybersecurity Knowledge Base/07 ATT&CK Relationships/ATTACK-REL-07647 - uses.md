---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0058"
target_object: "T1552.001"
stix_relationship_id: "relationship--1448897c-4b9a-44ef-a0ce-371f98c1f2f3"
---
# Relationship 7647: C0058 — uses → T1552.001

**Source object:** [[01 ATT&CK/C0058 - SharePoint ToolShell Exploitation|C0058: SharePoint ToolShell Exploitation]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1552.001 - Credentials In Files|T1552.001: Credentials In Files]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [SharePoint ToolShell Exploitation](https://attack.mitre.org/campaigns/C0058), threat actors accessed web.config and machine.config to extract MachineKey values, enabling them to forge legitimate VIEWSTATE tokens for future deserialization payloads.(Citation: Microsoft SharePoint Exploit JUL 2025)(Citation: Eye Research ToolShell JUL 2025)(Citation: Trend Micro SharePoint Attacks JUL 2025)(Citation: SentinelOne ToolShell JUL 2025)(Citation: Palo Alto SharePoint Vulnerabilities JUL 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1448897c-4b9a-44ef-a0ce-371f98c1f2f3`.
