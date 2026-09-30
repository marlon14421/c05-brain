---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0261"
target_object: "T1016"
stix_relationship_id: "relationship--a5bf547a-7fe3-4fa5-96f7-a932e583bf9e"
---
# Relationship 8016: S0261 — uses → T1016

**Source object:** [[01 ATT&CK/S0261 - Catchamas|S0261: Catchamas]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Catchamas](https://attack.mitre.org/software/S0261) gathers the Mac address, IP address, and the network adapter information from the victim’s machine.(Citation: Symantec Catchamas April 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a5bf547a-7fe3-4fa5-96f7-a932e583bf9e`.
