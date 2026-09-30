---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0090"
target_object: "T1025"
stix_relationship_id: "relationship--6d87588e-2202-4616-a536-e43a2606721b"
---
# Relationship 8428: S0090 — uses → T1025

**Source object:** [[01 ATT&CK/S0090 - Rover|S0090: Rover]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1025 - Data from Removable Media|T1025: Data from Removable Media]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Rover](https://attack.mitre.org/software/S0090) searches for files on attached removable drives based on a predefined list of file extensions every five seconds.(Citation: Palo Alto Rover)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6d87588e-2202-4616-a536-e43a2606721b`.
