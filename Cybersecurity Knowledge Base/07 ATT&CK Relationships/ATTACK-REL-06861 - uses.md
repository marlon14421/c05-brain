---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1035"
target_object: "T1036.004"
stix_relationship_id: "relationship--6f2f2822-6858-4c8c-9d33-62d2ee17f1af"
---
# Relationship 6861: G1035 — uses → T1036.004

**Source object:** [[01 ATT&CK/G1035 - Winter Vivern|G1035: Winter Vivern]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.004 - Masquerade Task or Service|T1036.004: Masquerade Task or Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Winter Vivern](https://attack.mitre.org/groups/G1035) has distributed malicious scripts and executables mimicking virus scanners.(Citation: SentinelOne WinterVivern 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6f2f2822-6858-4c8c-9d33-62d2ee17f1af`.
