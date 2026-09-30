---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0098"
target_object: "T1588.002"
stix_relationship_id: "relationship--17738bdd-24b9-44d0-a897-d1b861fd2636"
---
# Relationship 7315: G0098 — uses → T1588.002

**Source object:** [[01 ATT&CK/G0098 - BlackTech|G0098: BlackTech]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1588.002 - Tool|T1588.002: Tool]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BlackTech](https://attack.mitre.org/groups/G0098) has obtained and used tools such as Putty, SNScan, and [PsExec](https://attack.mitre.org/software/S0029) for its operations.(Citation: Symantec Palmerworm Sep 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--17738bdd-24b9-44d0-a897-d1b861fd2636`.
