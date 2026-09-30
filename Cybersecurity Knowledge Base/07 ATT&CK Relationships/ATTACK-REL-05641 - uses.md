---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0611"
target_object: "T1489"
stix_relationship_id: "relationship--056d19a6-8f3c-48a6-a459-69394e39fb9a"
---
# Relationship 5641: S0611 — uses → T1489

**Source object:** [[01 ATT&CK/S0611 - Clop|S0611: Clop]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1489 - Service Stop|T1489: Service Stop]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Clop](https://attack.mitre.org/software/S0611) can kill several processes and services related to backups and security solutions.(Citation: Unit42 Clop April 2021)(Citation: Mcafee Clop Aug 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--056d19a6-8f3c-48a6-a459-69394e39fb9a`.
