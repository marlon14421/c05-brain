---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0458"
target_object: "T1203"
stix_relationship_id: "relationship--76a3097b-808d-45a9-aa81-dce5ed6a45d3"
---
# Relationship 7986: S0458 — uses → T1203

**Source object:** [[01 ATT&CK/S0458 - Ramsay|S0458: Ramsay]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1203 - Exploitation for Client Execution|T1203: Exploitation for Client Execution]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Ramsay](https://attack.mitre.org/software/S0458) has been embedded in documents exploiting CVE-2017-0199, CVE-2017-11882, and CVE-2017-8570.(Citation: Eset Ramsay May 2020)(Citation: Antiy CERT Ramsay April 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--76a3097b-808d-45a9-aa81-dce5ed6a45d3`.
