---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0013"
target_object: "T1587.001"
stix_relationship_id: "relationship--caa820b8-5a7b-4704-88d9-380efff5a7a3"
---
# Relationship 6034: C0013 — uses → T1587.001

**Source object:** [[01 ATT&CK/C0013 - Operation Sharpshooter|C0013: Operation Sharpshooter]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1587.001 - Malware|T1587.001: Malware]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

For [Operation Sharpshooter](https://attack.mitre.org/campaigns/C0013), the threat actors used the [Rising Sun](https://attack.mitre.org/software/S0448) modular backdoor.(Citation: McAfee Sharpshooter December 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--caa820b8-5a7b-4704-88d9-380efff5a7a3`.
