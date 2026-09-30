---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0181"
target_object: "T1016"
stix_relationship_id: "relationship--760be456-6b72-4b86-b5aa-3297aa89bc4d"
---
# Relationship 6788: S0181 — uses → T1016

**Source object:** [[01 ATT&CK/S0181 - FALLCHILL|S0181: FALLCHILL]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FALLCHILL](https://attack.mitre.org/software/S0181) collects MAC address and local IP address information from the victim.(Citation: US-CERT FALLCHILL Nov 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--760be456-6b72-4b86-b5aa-3297aa89bc4d`.
