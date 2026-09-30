---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1047"
target_object: "T1037.004"
stix_relationship_id: "relationship--7b636fe8-0ea3-40de-92f9-76ba806352b9"
---
# Relationship 7623: G1047 — uses → T1037.004

**Source object:** [[01 ATT&CK/G1047 - Velvet Ant|G1047: Velvet Ant]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1037.004 - RC Scripts|T1037.004: RC Scripts]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Velvet Ant](https://attack.mitre.org/groups/G1047) used a modified `/etc/rc.local` file on compromised F5 BIG-IP devices to maintain persistence.(Citation: Sygnia VelvetAnt 2024A)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7b636fe8-0ea3-40de-92f9-76ba806352b9`.
