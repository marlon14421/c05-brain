---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1046"
target_object: "T1585.003"
stix_relationship_id: "relationship--055e53e9-1f00-47fe-906f-526b6ed6de30"
---
# Relationship 7892: G1046 — uses → T1585.003

**Source object:** [[01 ATT&CK/G1046 - Storm-1811|G1046: Storm-1811]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1585.003 - Cloud Accounts|T1585.003: Cloud Accounts]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Storm-1811](https://attack.mitre.org/groups/G1046) has created malicious accounts to enable activity via Microsoft Teams, typically spoofing various IT support and helpdesk themes.(Citation: Microsoft Storm-1811 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--055e53e9-1f00-47fe-906f-526b6ed6de30`.
