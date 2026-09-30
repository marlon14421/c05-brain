---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0109"
target_object: "T1059.003"
stix_relationship_id: "relationship--b3e4c3b6-0036-4968-b245-a4c36d3cd417"
---
# Relationship 5177: S0109 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0109 - WEBC2|S0109: WEBC2]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[WEBC2](https://attack.mitre.org/software/S0109) can open an interactive command shell.(Citation: Mandiant APT1)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b3e4c3b6-0036-4968-b245-a4c36d3cd417`.
