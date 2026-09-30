---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0055"
target_object: "T1027.011"
stix_relationship_id: "relationship--a23a8716-ffd4-407e-9890-99a416c35efa"
---
# Relationship 5857: C0055 — uses → T1027.011

**Source object:** [[01 ATT&CK/C0055 - Quad7 Activity|C0055: Quad7 Activity]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.011 - Fileless Storage|T1027.011: Fileless Storage]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Quad7 Activity](https://attack.mitre.org/campaigns/C0055) has infected victim network devices by storing artifacts in the /tmp directory which is volatile in memory and will clear its contents upon shutdown or restart.(Citation: Bitsight 7777 Botnet)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a23a8716-ffd4-407e-9890-99a416c35efa`.
