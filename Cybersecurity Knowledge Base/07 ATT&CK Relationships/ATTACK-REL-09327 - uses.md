---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1027"
target_object: "T1680"
stix_relationship_id: "relationship--69262212-bb89-43fc-8a80-ba492766e372"
---
# Relationship 9327: S1027 — uses → T1680

**Source object:** [[01 ATT&CK/S1027 - Heyoka Backdoor|S1027: Heyoka Backdoor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1680 - Local Storage Discovery|T1680: Local Storage Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Heyoka Backdoor](https://attack.mitre.org/software/S1027) can enumerate drives on a compromised host.(Citation: SentinelOne Aoqin Dragon June 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--69262212-bb89-43fc-8a80-ba492766e372`.
