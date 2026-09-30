---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1123"
target_object: "T1059.004"
stix_relationship_id: "relationship--8e5310df-b8df-49da-9ae0-dc6c3806e706"
---
# Relationship 8575: S1123 — uses → T1059.004

**Source object:** [[01 ATT&CK/S1123 - PITSTOP|S1123: PITSTOP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.004 - Unix Shell|T1059.004: Unix Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PITSTOP](https://attack.mitre.org/software/S1123) has the ability to receive shell commands over a Unix domain socket.(Citation: Mandiant Cutting Edge Part 3 February 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8e5310df-b8df-49da-9ae0-dc6c3806e706`.
