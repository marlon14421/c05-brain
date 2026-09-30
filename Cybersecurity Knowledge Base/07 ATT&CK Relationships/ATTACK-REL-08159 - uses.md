---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1207"
target_object: "T1059.010"
stix_relationship_id: "relationship--54800108-45e1-4e5d-9aaa-0374cf448367"
---
# Relationship 8159: S1207 — uses → T1059.010

**Source object:** [[01 ATT&CK/S1207 - XLoader|S1207: XLoader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.010 - AutoHotKey & AutoIT|T1059.010: AutoHotKey & AutoIT]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[XLoader](https://attack.mitre.org/software/S1207) can use an AutoIT script to decrypt a payload file, load it into victim memory, then execute it on the victim machine.(Citation: Google XLoader 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--54800108-45e1-4e5d-9aaa-0374cf448367`.
