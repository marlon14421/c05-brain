---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0018"
target_object: "T1190"
stix_relationship_id: "relationship--237d7c2e-503a-420c-bf94-047f5c42a646"
---
# Relationship 9484: C0018 — uses → T1190

**Source object:** [[01 ATT&CK/C0018 - C0018|C0018: C0018]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1190 - Exploit Public-Facing Application|T1190: Exploit Public-Facing Application]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [C0018](https://attack.mitre.org/campaigns/C0018), the threat actors exploited VMWare Horizon Unified Access Gateways that were vulnerable to several Log4Shell vulnerabilities, including CVE-2021-44228, CVE-2021-45046, CVE-2021-45105, and CVE-2021-44832.(Citation: Cisco Talos Avos Jun 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--237d7c2e-503a-420c-bf94-047f5c42a646`.
