---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1199"
target_object: "T1480"
stix_relationship_id: "relationship--ad02f6c8-9b1c-4d94-b6fd-fb953b9f8048"
---
# Relationship 9967: S1199 — uses → T1480

**Source object:** [[01 ATT&CK/S1199 - LockBit 2.0|S1199: LockBit 2.0]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1480 - Execution Guardrails|T1480: Execution Guardrails]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LockBit 2.0](https://attack.mitre.org/software/S1199) will not execute on hosts where the system language is set to a language spoken in the Commonwealth of Independent States region.(Citation: FBI Lockbit 2.0 FEB 2022)(Citation: Palo Alto Lockbit 2.0 JUN 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ad02f6c8-9b1c-4d94-b6fd-fb953b9f8048`.
