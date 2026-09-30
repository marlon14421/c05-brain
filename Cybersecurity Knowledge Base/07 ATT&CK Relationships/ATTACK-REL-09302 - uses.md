---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0052"
target_object: "T1588.002"
stix_relationship_id: "relationship--e36c6a15-c917-4817-93c3-7c78ceb1a702"
---
# Relationship 9302: C0052 — uses → T1588.002

**Source object:** [[01 ATT&CK/C0052 - SPACEHOP Activity|C0052: SPACEHOP Activity]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1588.002 - Tool|T1588.002: Tool]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SPACEHOP Activity](https://attack.mitre.org/campaigns/C0052) leverages a C2 framework sourced from a publicly-available Github repository for administration of relay nodes.(Citation: ORB Mandiant)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e36c6a15-c917-4817-93c3-7c78ceb1a702`.
