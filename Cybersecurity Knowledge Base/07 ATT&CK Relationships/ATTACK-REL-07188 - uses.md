---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1081"
target_object: "T1033"
stix_relationship_id: "relationship--5ea72071-0251-4826-8a7b-7677ec52eadb"
---
# Relationship 7188: S1081 — uses → T1033

**Source object:** [[01 ATT&CK/S1081 - BADHATCH|S1081: BADHATCH]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BADHATCH](https://attack.mitre.org/software/S1081) can obtain logged user information from a compromised machine and can execute the command `whoami.exe`.(Citation: BitDefender BADHATCH Mar 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5ea72071-0251-4826-8a7b-7677ec52eadb`.
