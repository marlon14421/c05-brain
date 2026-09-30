---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0045"
target_object: "T1082"
stix_relationship_id: "relationship--090a553a-b863-4214-aa3b-cf8ea7ba2d68"
---
# Relationship 8662: S0045 — uses → T1082

**Source object:** [[01 ATT&CK/S0045 - ADVSTORESHELL|S0045: ADVSTORESHELL]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ADVSTORESHELL](https://attack.mitre.org/software/S0045) can run [Systeminfo](https://attack.mitre.org/software/S0096) to gather information about the victim.(Citation: ESET Sednit Part 2)(Citation: Bitdefender APT28 Dec 2015)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--090a553a-b863-4214-aa3b-cf8ea7ba2d68`.
