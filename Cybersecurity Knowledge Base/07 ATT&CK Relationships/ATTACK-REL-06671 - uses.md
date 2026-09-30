---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1184"
target_object: "T1480"
stix_relationship_id: "relationship--e2a0910e-16a9-493e-8c0e-d5557e77e3b0"
---
# Relationship 6671: S1184 — uses → T1480

**Source object:** [[01 ATT&CK/S1184 - BOLDMOVE|S1184: BOLDMOVE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1480 - Execution Guardrails|T1480: Execution Guardrails]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BOLDMOVE](https://attack.mitre.org/software/S1184) verifies it is executing from a specific path during execution.(Citation: Google Cloud BOLDMOVE 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e2a0910e-16a9-493e-8c0e-d5557e77e3b0`.
