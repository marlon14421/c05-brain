---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0044"
target_object: "T1115"
stix_relationship_id: "relationship--83aac36d-6dfa-4c27-b1b1-c200c9240eb9"
---
# Relationship 7175: S0044 — uses → T1115

**Source object:** [[01 ATT&CK/S0044 - JHUHUGIT|S0044: JHUHUGIT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1115 - Clipboard Data|T1115: Clipboard Data]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

A [JHUHUGIT](https://attack.mitre.org/software/S0044) variant accesses a screenshot saved in the clipboard and converts it to a JPG image.(Citation: Unit 42 Playbook Dec 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--83aac36d-6dfa-4c27-b1b1-c200c9240eb9`.
