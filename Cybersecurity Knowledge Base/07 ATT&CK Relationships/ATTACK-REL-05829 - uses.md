---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0377"
target_object: "T1014"
stix_relationship_id: "relationship--05a3d203-4b38-4f38-a015-dcfe3bdf9c07"
---
# Relationship 5829: S0377 — uses → T1014

**Source object:** [[01 ATT&CK/S0377 - Ebury|S0377: Ebury]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1014 - Rootkit|T1014: Rootkit]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Ebury](https://attack.mitre.org/software/S0377) acts as a user land rootkit using the SSH service.(Citation: ESET Ebury Oct 2017)(Citation: ESET Ebury May 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--05a3d203-4b38-4f38-a015-dcfe3bdf9c07`.
