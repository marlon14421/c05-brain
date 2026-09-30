---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9014"
target_object: "T1059.008"
stix_relationship_id: "relationship--e47457bf-aa6a-414c-89df-78b442e116dc"
---
# Relationship 7377: S9014 — uses → T1059.008

**Source object:** [[01 ATT&CK/S9014 - PHASEJAM|S9014: PHASEJAM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.008 - Network Device CLI|T1059.008: Network Device CLI]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PHASEJAM](https://attack.mitre.org/software/S9014) has leveraged native commands associated with the compromised network appliance to execute code.(Citation: Google UNC5221 Ivanti January 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e47457bf-aa6a-414c-89df-78b442e116dc`.
