---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1018"
target_object: "T1204.001"
stix_relationship_id: "relationship--e877f75e-4b57-4328-a17c-a7c46929ae84"
---
# Relationship 8594: S1018 — uses → T1204.001

**Source object:** [[01 ATT&CK/S1018 - Saint Bot|S1018: Saint Bot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.001 - Malicious Link|T1204.001: Malicious Link]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Saint Bot](https://attack.mitre.org/software/S1018) has relied on users to click on a malicious link delivered via a spearphishing.(Citation: Palo Alto Unit 42 OutSteel SaintBot February 2022 )

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e877f75e-4b57-4328-a17c-a7c46929ae84`.
