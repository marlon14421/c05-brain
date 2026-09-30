---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1014"
target_object: "T1587.001"
stix_relationship_id: "relationship--3e26385f-0aa0-44a3-8830-978610a1680d"
---
# Relationship 5645: G1014 — uses → T1587.001

**Source object:** [[01 ATT&CK/G1014 - LuminousMoth|G1014: LuminousMoth]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1587.001 - Malware|T1587.001: Malware]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LuminousMoth](https://attack.mitre.org/groups/G1014) has used unique malware for information theft and exfiltration.(Citation: Kaspersky LuminousMoth July 2021)(Citation: Bitdefender LuminousMoth July 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3e26385f-0aa0-44a3-8830-978610a1680d`.
