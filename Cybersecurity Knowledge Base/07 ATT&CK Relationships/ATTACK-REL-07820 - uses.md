---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1086"
target_object: "T1204.002"
stix_relationship_id: "relationship--69d1d811-fb2f-43cc-99bb-989769dd4ffb"
---
# Relationship 7820: S1086 — uses → T1204.002

**Source object:** [[01 ATT&CK/S1086 - Snip3|S1086: Snip3]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Snip3](https://attack.mitre.org/software/S1086) can gain execution through the download of visual basic files.(Citation: Morphisec Snip3 May 2021)(Citation: Telefonica Snip3 December 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--69d1d811-fb2f-43cc-99bb-989769dd4ffb`.
