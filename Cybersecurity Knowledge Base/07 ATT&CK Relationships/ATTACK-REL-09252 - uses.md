---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0012"
target_object: "T1087.001"
stix_relationship_id: "relationship--71819612-01e7-48cf-89ea-09da4f05c2e8"
---
# Relationship 9252: C0012 — uses → T1087.001

**Source object:** [[01 ATT&CK/C0012 - Operation CuckooBees|C0012: Operation CuckooBees]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1087.001 - Local Account|T1087.001: Local Account]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Operation CuckooBees](https://attack.mitre.org/campaigns/C0012), the threat actors used the `net user` command to gather account information.(Citation: Cybereason OperationCuckooBees May 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--71819612-01e7-48cf-89ea-09da4f05c2e8`.
