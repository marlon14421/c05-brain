---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0045"
target_object: "T1546.015"
stix_relationship_id: "relationship--075e7d33-8d5c-4016-9a24-dc6e61f56fcd"
---
# Relationship 9109: S0045 — uses → T1546.015

**Source object:** [[01 ATT&CK/S0045 - ADVSTORESHELL|S0045: ADVSTORESHELL]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1546.015 - Component Object Model Hijacking|T1546.015: Component Object Model Hijacking]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Some variants of [ADVSTORESHELL](https://attack.mitre.org/software/S0045) achieve persistence by registering the payload as a Shell Icon Overlay handler COM object.(Citation: ESET Sednit Part 2)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--075e7d33-8d5c-4016-9a24-dc6e61f56fcd`.
