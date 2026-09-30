---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0410"
target_object: "T1543.002"
stix_relationship_id: "relationship--8c9c075a-0c9a-45ef-a4cb-53095c2664a7"
---
# Relationship 9553: S0410 — uses → T1543.002

**Source object:** [[01 ATT&CK/S0410 - Fysbis|S0410: Fysbis]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1543.002 - Systemd Service|T1543.002: Systemd Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Fysbis](https://attack.mitre.org/software/S0410) has established persistence using a systemd service.(Citation: Fysbis Dr Web Analysis)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8c9c075a-0c9a-45ef-a4cb-53095c2664a7`.
