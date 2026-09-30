---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1086"
target_object: "T1566.002"
stix_relationship_id: "relationship--b1ed7715-2145-4b26-b414-8f83a29e1f74"
---
# Relationship 8316: S1086 — uses → T1566.002

**Source object:** [[01 ATT&CK/S1086 - Snip3|S1086: Snip3]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.002 - Spearphishing Link|T1566.002: Spearphishing Link]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Snip3](https://attack.mitre.org/software/S1086) has been delivered to victims through e-mail links to malicious files.(Citation: Telefonica Snip3 December 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b1ed7715-2145-4b26-b414-8f83a29e1f74`.
