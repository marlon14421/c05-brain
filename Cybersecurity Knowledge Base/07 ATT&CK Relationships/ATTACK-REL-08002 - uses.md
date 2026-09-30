---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0106"
target_object: "T1027.004"
stix_relationship_id: "relationship--47440b3d-e6ef-4f7d-b732-453d1684424a"
---
# Relationship 8002: G0106 — uses → T1027.004

**Source object:** [[01 ATT&CK/G0106 - Rocke|G0106: Rocke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.004 - Compile After Delivery|T1027.004: Compile After Delivery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Rocke](https://attack.mitre.org/groups/G0106) has compiled malware, delivered to victims as .c files, with the GNU Compiler Collection (GCC).(Citation: Anomali Rocke March 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--47440b3d-e6ef-4f7d-b732-453d1684424a`.
