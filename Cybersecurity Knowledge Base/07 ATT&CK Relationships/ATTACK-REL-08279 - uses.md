---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0008"
target_object: "T1218.011"
stix_relationship_id: "relationship--539f8bc3-3fb4-43af-8918-9a65239cdff6"
---
# Relationship 8279: G0008 — uses → T1218.011

**Source object:** [[01 ATT&CK/G0008 - Carbanak|G0008: Carbanak]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.011 - Rundll32|T1218.011: Rundll32]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Carbanak](https://attack.mitre.org/groups/G0008) installs VNC server software that executes through rundll32.(Citation: Kaspersky Carbanak)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--539f8bc3-3fb4-43af-8918-9a65239cdff6`.
