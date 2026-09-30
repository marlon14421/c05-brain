---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0137"
target_object: "T1204.002"
stix_relationship_id: "relationship--471ea836-ef54-4306-b131-cf66de5811c4"
---
# Relationship 5258: G0137 — uses → T1204.002

**Source object:** [[01 ATT&CK/G0137 - Ferocious Kitten|G0137: Ferocious Kitten]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Ferocious Kitten](https://attack.mitre.org/groups/G0137) has attempted to convince victims to enable malicious content within a spearphishing email by including an odd decoy message.(Citation: Kaspersky Ferocious Kitten Jun 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--471ea836-ef54-4306-b131-cf66de5811c4`.
