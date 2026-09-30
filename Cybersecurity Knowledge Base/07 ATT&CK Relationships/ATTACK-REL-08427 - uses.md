---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0006"
target_object: "T1106"
stix_relationship_id: "relationship--28427b29-2088-44f7-8acd-5df104dcb8ee"
---
# Relationship 8427: C0006 — uses → T1106

**Source object:** [[01 ATT&CK/C0006 - Operation Honeybee|C0006: Operation Honeybee]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Operation Honeybee](https://attack.mitre.org/campaigns/C0006), the threat actors deployed malware that used API calls, including `CreateProcessAsUser`.(Citation: McAfee Honeybee)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--28427b29-2088-44f7-8acd-5df104dcb8ee`.
