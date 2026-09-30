---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1106"
target_object: "T1016"
stix_relationship_id: "relationship--cad1f2d3-c3c2-4f55-863e-0de712cd84b7"
---
# Relationship 9052: S1106 — uses → T1016

**Source object:** [[01 ATT&CK/S1106 - NGLite|S1106: NGLite]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[NGLite](https://attack.mitre.org/software/S1106) identifies the victim system MAC and IPv4 addresses and uses these to establish a victim identifier.(Citation: NGLite Trojan)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cad1f2d3-c3c2-4f55-863e-0de712cd84b7`.
