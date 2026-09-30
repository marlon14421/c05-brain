---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1111"
target_object: "T1082"
stix_relationship_id: "relationship--011286cc-53bc-4910-bf38-79f1d79fc707"
---
# Relationship 8674: S1111 — uses → T1082

**Source object:** [[01 ATT&CK/S1111 - DarkGate|S1111: DarkGate]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DarkGate](https://attack.mitre.org/software/S1111) will gather various system information such as domain, display adapter description, operating system type and version, processor type, and RAM amount.(Citation: Ensilo Darkgate 2018)(Citation: Rapid7 BlackBasta 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--011286cc-53bc-4910-bf38-79f1d79fc707`.
