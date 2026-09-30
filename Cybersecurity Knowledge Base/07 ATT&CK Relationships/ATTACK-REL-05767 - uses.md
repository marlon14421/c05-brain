---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1184"
target_object: "T1190"
stix_relationship_id: "relationship--a7fbea9e-99a2-4319-b159-f4cb18908c27"
---
# Relationship 5767: S1184 — uses → T1190

**Source object:** [[01 ATT&CK/S1184 - BOLDMOVE|S1184: BOLDMOVE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1190 - Exploit Public-Facing Application|T1190: Exploit Public-Facing Application]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BOLDMOVE](https://attack.mitre.org/software/S1184) is associated with exploitation of CVE-2022-49475 in FortiOS.(Citation: Google Cloud BOLDMOVE 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a7fbea9e-99a2-4319-b159-f4cb18908c27`.
