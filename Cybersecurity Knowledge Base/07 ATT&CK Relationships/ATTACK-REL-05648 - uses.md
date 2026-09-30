---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0070"
target_object: "T1566.003"
stix_relationship_id: "relationship--b4174e7a-3b60-4697-a006-84edb81622cd"
---
# Relationship 5648: G0070 — uses → T1566.003

**Source object:** [[01 ATT&CK/G0070 - Dark Caracal|G0070: Dark Caracal]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.003 - Spearphishing via Service|T1566.003: Spearphishing via Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Dark Caracal](https://attack.mitre.org/groups/G0070) spearphished victims via Facebook and Whatsapp.(Citation: Lookout Dark Caracal Jan 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b4174e7a-3b60-4697-a006-84edb81622cd`.
