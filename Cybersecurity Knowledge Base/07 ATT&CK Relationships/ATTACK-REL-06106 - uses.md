---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0184"
target_object: "T1057"
stix_relationship_id: "relationship--408db284-4c7a-4ad4-8399-90a8102b4bfa"
---
# Relationship 6106: S0184 — uses → T1057

**Source object:** [[01 ATT&CK/S0184 - POWRUNER|S0184: POWRUNER]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[POWRUNER](https://attack.mitre.org/software/S0184) may collect process information by running tasklist on a victim.(Citation: FireEye APT34 Dec 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--408db284-4c7a-4ad4-8399-90a8102b4bfa`.
