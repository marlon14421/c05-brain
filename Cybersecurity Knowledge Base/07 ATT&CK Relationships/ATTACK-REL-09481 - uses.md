---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1244"
target_object: "T1135"
stix_relationship_id: "relationship--160fe071-f28f-47c3-a87c-e7cfc9e72f31"
---
# Relationship 9481: S1244 — uses → T1135

**Source object:** [[01 ATT&CK/S1244 - Medusa Ransomware|S1244: Medusa Ransomware]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1135 - Network Share Discovery|T1135: Network Share Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Medusa Ransomware](https://attack.mitre.org/software/S1244) has identified networked drives.(Citation: Palo Alto Unit 42 Medusa Group Medusa Ransomware January 2024)(Citation: Broadcom Medusa Ransomware Medusa Group March 2025)(Citation: Security Scorecard Medusa Ransomware January 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--160fe071-f28f-47c3-a87c-e7cfc9e72f31`.
