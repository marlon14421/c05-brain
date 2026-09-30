---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0501"
target_object: "T1057"
stix_relationship_id: "relationship--8ead6aa1-dbbe-4e8f-b542-66af9b5f2c33"
---
# Relationship 7423: S0501 — uses → T1057

**Source object:** [[01 ATT&CK/S0501 - PipeMon|S0501: PipeMon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PipeMon](https://attack.mitre.org/software/S0501) can iterate over the running processes to find a suitable injection target.(Citation: ESET PipeMon May 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8ead6aa1-dbbe-4e8f-b542-66af9b5f2c33`.
