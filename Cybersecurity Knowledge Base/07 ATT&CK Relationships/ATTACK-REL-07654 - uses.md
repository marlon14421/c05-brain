---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0697"
target_object: "T1083"
stix_relationship_id: "relationship--6435a96b-f3b5-4a16-876f-901650257d36"
---
# Relationship 7654: S0697 — uses → T1083

**Source object:** [[01 ATT&CK/S0697 - HermeticWiper|S0697: HermeticWiper]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HermeticWiper](https://attack.mitre.org/software/S0697) can enumerate common folders such as My Documents, Desktop, and AppData.(Citation: SentinelOne Hermetic Wiper February 2022)(Citation: Qualys Hermetic Wiper March 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6435a96b-f3b5-4a16-876f-901650257d36`.
