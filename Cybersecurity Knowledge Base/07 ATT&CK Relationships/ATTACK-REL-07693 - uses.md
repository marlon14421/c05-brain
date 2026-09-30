---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0633"
target_object: "T1134"
stix_relationship_id: "relationship--5a25798a-eca1-4841-b422-95aa3bf025e3"
---
# Relationship 7693: S0633 — uses → T1134

**Source object:** [[01 ATT&CK/S0633 - Sliver|S0633: Sliver]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1134 - Access Token Manipulation|T1134: Access Token Manipulation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Sliver](https://attack.mitre.org/software/S0633) has the ability to manipulate user tokens on targeted Windows systems.(Citation: Bishop Fox Sliver Framework August 2019)(Citation: GitHub Sliver C2)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5a25798a-eca1-4841-b422-95aa3bf025e3`.
