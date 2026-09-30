---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0681"
target_object: "T1113"
stix_relationship_id: "relationship--638b21af-b5d5-44dd-9d14-ea3c2be3eb4e"
---
# Relationship 8710: S0681 — uses → T1113

**Source object:** [[01 ATT&CK/S0681 - Lizar|S0681: Lizar]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Lizar](https://attack.mitre.org/software/S0681) can take JPEG screenshots of an infected system.(Citation: Threatpost Lizar May 2021)(Citation: BiZone Lizar May 2021) [Lizar](https://attack.mitre.org/software/S0681) has also used a plugin to take a screenshot of the infected system.(Citation: BiZone Lizar May 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--638b21af-b5d5-44dd-9d14-ea3c2be3eb4e`.
