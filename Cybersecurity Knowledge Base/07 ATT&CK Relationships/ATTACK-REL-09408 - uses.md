---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0053"
target_object: "T1059"
stix_relationship_id: "relationship--828cc716-d3ea-49e8-80a8-67d471a62017"
---
# Relationship 9408: C0053 — uses → T1059

**Source object:** [[01 ATT&CK/C0053 - FLORAHOX Activity|C0053: FLORAHOX Activity]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059 - Command and Scripting Interpreter|T1059: Command and Scripting Interpreter]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FLORAHOX Activity](https://attack.mitre.org/campaigns/C0053) has executed PHP and Shell scripts to identify and infect subsequent routers for the ORB network.(Citation: ORB Mandiant)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--828cc716-d3ea-49e8-80a8-67d471a62017`.
