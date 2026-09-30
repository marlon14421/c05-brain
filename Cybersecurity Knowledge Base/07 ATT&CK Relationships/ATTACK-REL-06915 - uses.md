---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1052"
target_object: "T1480"
stix_relationship_id: "relationship--03cb8f9a-7ad7-4aa8-966f-bf768023eb89"
---
# Relationship 6915: S1052 — uses → T1480

**Source object:** [[01 ATT&CK/S1052 - DEADEYE|S1052: DEADEYE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1480 - Execution Guardrails|T1480: Execution Guardrails]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DEADEYE](https://attack.mitre.org/software/S1052) can ensure it executes only on intended systems by identifying the victim's volume serial number, hostname, and/or DNS domain.(Citation: Mandiant APT41)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--03cb8f9a-7ad7-4aa8-966f-bf768023eb89`.
