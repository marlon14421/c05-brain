---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1106"
target_object: "T1033"
stix_relationship_id: "relationship--8a0ac9c9-e8e2-44a2-b2b0-87b4b4fa90fb"
---
# Relationship 7240: S1106 — uses → T1033

**Source object:** [[01 ATT&CK/S1106 - NGLite|S1106: NGLite]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[NGLite](https://attack.mitre.org/software/S1106) will run the whoami command to gather system information and return this to the command and control server.(Citation: NGLite Trojan)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8a0ac9c9-e8e2-44a2-b2b0-87b4b4fa90fb`.
