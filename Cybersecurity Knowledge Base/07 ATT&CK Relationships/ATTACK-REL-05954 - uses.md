---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0179"
target_object: "T1003.007"
stix_relationship_id: "relationship--d3b810ed-0be4-448b-b1ac-aa3a7dd16c91"
---
# Relationship 5954: S0179 — uses → T1003.007

**Source object:** [[01 ATT&CK/S0179 - MimiPenguin|S0179: MimiPenguin]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1003.007 - Proc Filesystem|T1003.007: Proc Filesystem]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MimiPenguin](https://attack.mitre.org/software/S0179) can use the ` /maps` and ` /mem` file to search for regex patterns and dump the process memory.(Citation: MimiPenguin GitHub May 2017)(Citation: Picus Labs Proc cump 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d3b810ed-0be4-448b-b1ac-aa3a7dd16c91`.
