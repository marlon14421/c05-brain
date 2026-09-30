---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0012"
target_object: "T1033"
stix_relationship_id: "relationship--71f80d4d-daf5-4da2-811b-0ebd3365b79c"
---
# Relationship 7718: C0012 — uses → T1033

**Source object:** [[01 ATT&CK/C0012 - Operation CuckooBees|C0012: Operation CuckooBees]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Operation CuckooBees](https://attack.mitre.org/campaigns/C0012), the threat actors used the `query user` and `whoami` commands as part of their advanced reconnaissance.(Citation: Cybereason OperationCuckooBees May 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--71f80d4d-daf5-4da2-811b-0ebd3365b79c`.
