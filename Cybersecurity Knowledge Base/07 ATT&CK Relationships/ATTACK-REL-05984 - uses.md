---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0475"
target_object: "T1137.001"
stix_relationship_id: "relationship--66ce5052-08d8-4160-a8c9-f3e6b9e5cd1f"
---
# Relationship 5984: S0475 — uses → T1137.001

**Source object:** [[01 ATT&CK/S0475 - BackConfig|S0475: BackConfig]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1137.001 - Office Template Macros|T1137.001: Office Template Macros]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BackConfig](https://attack.mitre.org/software/S0475) has the ability to use hidden columns in Excel spreadsheets to store executable files or commands for VBA macros.(Citation: Unit 42 BackConfig May 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--66ce5052-08d8-4160-a8c9-f3e6b9e5cd1f`.
