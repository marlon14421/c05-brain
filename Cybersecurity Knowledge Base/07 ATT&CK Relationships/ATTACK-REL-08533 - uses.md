---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1244"
target_object: "T1559"
stix_relationship_id: "relationship--9d753094-3f5a-4d38-88dd-13289e1d8318"
---
# Relationship 8533: S1244 — uses → T1559

**Source object:** [[01 ATT&CK/S1244 - Medusa Ransomware|S1244: Medusa Ransomware]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1559 - Inter-Process Communication|T1559: Inter-Process Communication]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Medusa Ransomware](https://attack.mitre.org/software/S1244) has leveraged the `CreatePipe` API to enable inter-process communication.(Citation: Security Scorecard Medusa Ransomware January 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9d753094-3f5a-4d38-88dd-13289e1d8318`.
