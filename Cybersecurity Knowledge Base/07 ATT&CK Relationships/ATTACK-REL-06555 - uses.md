---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1053"
target_object: "T1526"
stix_relationship_id: "relationship--52288e4e-f430-472a-b5aa-f875f1007d73"
---
# Relationship 6555: G1053 — uses → T1526

**Source object:** [[01 ATT&CK/G1053 - Storm-0501|G1053: Storm-0501]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1526 - Cloud Service Discovery|T1526: Cloud Service Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Storm-0501](https://attack.mitre.org/groups/G1053) has discovered the victim environment’s protections to include Azure policies, resource locks, and Azure Storage immutability policies.(Citation: Microsoft Storm-0501 Embargo Ransomware August 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--52288e4e-f430-472a-b5aa-f875f1007d73`.
