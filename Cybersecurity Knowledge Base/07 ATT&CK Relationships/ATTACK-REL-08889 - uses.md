---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0192"
target_object: "T1049"
stix_relationship_id: "relationship--eb3a838e-f6dd-4e9b-8edf-fc652adde117"
---
# Relationship 8889: S0192 — uses → T1049

**Source object:** [[01 ATT&CK/S0192 - Pupy|S0192: Pupy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1049 - System Network Connections Discovery|T1049: System Network Connections Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Pupy](https://attack.mitre.org/software/S0192) has a built-in utility command for netstat , can do net session through PowerView, and has an interactive shell which can be used to discover additional information.(Citation: GitHub Pupy)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--eb3a838e-f6dd-4e9b-8edf-fc652adde117`.
