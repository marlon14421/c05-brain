---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0192"
target_object: "T1136.002"
stix_relationship_id: "relationship--3aab83a8-eeda-4fdd-a103-d7f1e8d02989"
---
# Relationship 7046: S0192 — uses → T1136.002

**Source object:** [[01 ATT&CK/S0192 - Pupy|S0192: Pupy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1136.002 - Domain Account|T1136.002: Domain Account]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Pupy](https://attack.mitre.org/software/S0192) can user PowerView to execute “net user” commands and create domain accounts.(Citation: GitHub Pupy)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3aab83a8-eeda-4fdd-a103-d7f1e8d02989`.
