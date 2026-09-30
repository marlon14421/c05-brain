---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1203"
target_object: "T1016"
stix_relationship_id: "relationship--475d258d-4ebb-41c5-861c-904c75036cf3"
---
# Relationship 5491: S1203 — uses → T1016

**Source object:** [[01 ATT&CK/S1203 - J-magic|S1203: J-magic]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[J-magic](https://attack.mitre.org/software/S1203) can compare the host and remote IPs to check if a received packet is from the infected machine.(Citation: Lumen J-Magic JAN 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--475d258d-4ebb-41c5-861c-904c75036cf3`.
