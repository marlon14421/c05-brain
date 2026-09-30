---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1043"
target_object: "S0099"
stix_relationship_id: "relationship--8f097447-429c-4a28-b333-78936f11e0c0"
---
# Relationship 9133: G1043 — uses → S0099

**Source object:** [[01 ATT&CK/G1043 - BlackByte|G1043: BlackByte]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0099 - Arp|S0099: Arp]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BlackByte](https://attack.mitre.org/groups/G1043) used [Arp](https://attack.mitre.org/software/S0099) to identify connected hosts in victim networks.(Citation: FBI BlackByte 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8f097447-429c-4a28-b333-78936f11e0c0`.
