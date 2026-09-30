---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0390"
target_object: "T1140"
stix_relationship_id: "relationship--b7f13afc-0e1c-4142-b05c-def10c17a8d6"
---
# Relationship 6974: S0390 — uses → T1140

**Source object:** [[01 ATT&CK/S0390 - SQLRat|S0390: SQLRat]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SQLRat](https://attack.mitre.org/software/S0390) has scripts that are responsible for deobfuscating additional scripts.(Citation: Flashpoint FIN 7 March 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b7f13afc-0e1c-4142-b05c-def10c17a8d6`.
