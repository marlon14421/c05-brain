---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1051"
target_object: "T1072"
stix_relationship_id: "relationship--f5c91894-57ae-4e16-945f-8ad04f9c2d85"
---
# Relationship 7911: G1051 — uses → T1072

**Source object:** [[01 ATT&CK/G1051 - Medusa Group|G1051: Medusa Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1072 - Software Deployment Tools|T1072: Software Deployment Tools]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Medusa Group](https://attack.mitre.org/groups/G1051) has utilized software deployment and management solutions to deploy their encryption payload to include BigFix and PDQ Deploy.(Citation: CISA Medusa Group Medusa Ransomware March 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f5c91894-57ae-4e16-945f-8ad04f9c2d85`.
