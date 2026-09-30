---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1239"
target_object: "T1036.005"
stix_relationship_id: "relationship--0def160c-4c74-477c-91b4-005603097cf2"
---
# Relationship 8758: S1239 — uses → T1036.005

**Source object:** [[01 ATT&CK/S1239 - TONESHELL|S1239: TONESHELL]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TONESHELL](https://attack.mitre.org/software/S1239) has renamed malicious files to mimic legitimate file names and file extensions.(Citation: 2022 November_TrendMicro_Earth Preta_Toneshell_Pubload) [TONESHELL](https://attack.mitre.org/software/S1239) has also masqueraded as legitimate file names to include LogMeIn.dll.(Citation: Zscaler)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0def160c-4c74-477c-91b4-005603097cf2`.
