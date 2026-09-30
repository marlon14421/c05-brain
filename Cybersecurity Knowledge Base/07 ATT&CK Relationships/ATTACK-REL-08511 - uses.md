---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0235"
target_object: "T1547.013"
stix_relationship_id: "relationship--c848ea14-292b-4ad8-ab58-70b26b023275"
---
# Relationship 8511: S0235 — uses → T1547.013

**Source object:** [[01 ATT&CK/S0235 - CrossRAT|S0235: CrossRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.013 - XDG Autostart Entries|T1547.013: XDG Autostart Entries]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CrossRAT](https://attack.mitre.org/software/S0235) can use an XDG Autostart to establish persistence.(Citation: Red Canary Netwire Linux 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c848ea14-292b-4ad8-ab58-70b26b023275`.
