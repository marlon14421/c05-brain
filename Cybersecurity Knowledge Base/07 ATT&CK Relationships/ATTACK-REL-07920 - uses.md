---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0692"
target_object: "T1056.002"
stix_relationship_id: "relationship--e6553c0d-9f67-412a-8e72-fad7059c35b1"
---
# Relationship 7920: S0692 — uses → T1056.002

**Source object:** [[01 ATT&CK/S0692 - SILENTTRINITY|S0692: SILENTTRINITY]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.002 - GUI Input Capture|T1056.002: GUI Input Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SILENTTRINITY](https://attack.mitre.org/software/S0692)'s `credphisher.py` module can prompt a current user for their credentials.(Citation: GitHub SILENTTRINITY Modules July 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e6553c0d-9f67-412a-8e72-fad7059c35b1`.
