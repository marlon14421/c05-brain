---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1180"
target_object: "T1570"
stix_relationship_id: "relationship--61c4b285-ef0a-4cf6-ad8b-3599660211d4"
---
# Relationship 8299: S1180 — uses → T1570

**Source object:** [[01 ATT&CK/S1180 - BlackByte Ransomware|S1180: BlackByte Ransomware]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1570 - Lateral Tool Transfer|T1570: Lateral Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BlackByte Ransomware](https://attack.mitre.org/software/S1180) spreads itself laterally by writing the JavaScript launcher file to mapped shared folders.(Citation: Trustwave BlackByte 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--61c4b285-ef0a-4cf6-ad8b-3599660211d4`.
