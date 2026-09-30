---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0046"
target_object: "T1546.011"
stix_relationship_id: "relationship--506acc8a-e691-4f4e-b69f-bfab84cf2c73"
---
# Relationship 8353: G0046 — uses → T1546.011

**Source object:** [[01 ATT&CK/G0046 - FIN7|G0046: FIN7]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1546.011 - Application Shimming|T1546.011: Application Shimming]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FIN7](https://attack.mitre.org/groups/G0046) has used application shim databases for persistence.(Citation: FireEye FIN7 Shim Databases)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--506acc8a-e691-4f4e-b69f-bfab84cf2c73`.
