---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1227"
target_object: "T1095"
stix_relationship_id: "relationship--e98a8ed8-24eb-4390-b528-5e023eafe69e"
---
# Relationship 5660: S1227 — uses → T1095

**Source object:** [[01 ATT&CK/S1227 - StarProxy|S1227: StarProxy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1095 - Non-Application Layer Protocol|T1095: Non-Application Layer Protocol]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[StarProxy](https://attack.mitre.org/software/S1227) has used TCP for C2 communications to target IPs or domains. [StarProxy](https://attack.mitre.org/software/S1227) contained code to support both UDP and TCP connections.(Citation: Zscaler)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e98a8ed8-24eb-4390-b528-5e023eafe69e`.
