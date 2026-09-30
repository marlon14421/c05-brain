---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1200"
target_object: "T1480"
stix_relationship_id: "relationship--99174f3b-8c31-4d4d-b803-0a6bff16e859"
---
# Relationship 5271: S1200 — uses → T1480

**Source object:** [[01 ATT&CK/S1200 - StealBit|S1200: StealBit]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1480 - Execution Guardrails|T1480: Execution Guardrails]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[StealBit](https://attack.mitre.org/software/S1200) will execute an empty infinite loop if it detects it is being run in the context of a debugger.(Citation: Cybereason StealBit Exfiltration Tool)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--99174f3b-8c31-4d4d-b803-0a6bff16e859`.
