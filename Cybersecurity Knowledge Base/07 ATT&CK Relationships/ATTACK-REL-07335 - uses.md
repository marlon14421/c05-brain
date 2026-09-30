---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0251"
target_object: "T1132.001"
stix_relationship_id: "relationship--d514d73a-27de-409d-bff9-d7e48f2859a6"
---
# Relationship 7335: S0251 — uses → T1132.001

**Source object:** [[01 ATT&CK/S0251 - Zebrocy|S0251: Zebrocy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1132.001 - Standard Encoding|T1132.001: Standard Encoding]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Zebrocy](https://attack.mitre.org/software/S0251) has used URL/Percent Encoding on data exfiltrated via HTTP POST requests.(Citation: Accenture SNAKEMACKEREL Nov 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d514d73a-27de-409d-bff9-d7e48f2859a6`.
