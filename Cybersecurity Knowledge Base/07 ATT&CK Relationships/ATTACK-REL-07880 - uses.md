---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0062"
target_object: "T1203"
stix_relationship_id: "relationship--8a9d92e5-e9b5-40bd-8cc4-c4cc5ed9fdd4"
---
# Relationship 7880: G0062 — uses → T1203

**Source object:** [[01 ATT&CK/G0062 - TA459|G0062: TA459]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1203 - Exploitation for Client Execution|T1203: Exploitation for Client Execution]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TA459](https://attack.mitre.org/groups/G0062) has exploited Microsoft Word vulnerability CVE-2017-0199 for execution.(Citation: Proofpoint TA459 April 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8a9d92e5-e9b5-40bd-8cc4-c4cc5ed9fdd4`.
