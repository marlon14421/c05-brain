---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0073"
target_object: "T1112"
stix_relationship_id: "relationship--45f35ec0-73a8-42a6-b879-d800d27211c8"
---
# Relationship 5326: G0073 — uses → T1112

**Source object:** [[01 ATT&CK/G0073 - APT19|G0073: APT19]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1112 - Modify Registry|T1112: Modify Registry]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT19](https://attack.mitre.org/groups/G0073) uses a Port 22 malware variant to modify several Registry keys.(Citation: Unit 42 C0d0so0 Jan 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--45f35ec0-73a8-42a6-b879-d800d27211c8`.
