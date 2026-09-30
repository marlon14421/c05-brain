---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1008"
target_object: "T1105"
stix_relationship_id: "relationship--1d2111ce-5034-472a-89a7-1818d11280fb"
---
# Relationship 9968: G1008 — uses → T1105

**Source object:** [[01 ATT&CK/G1008 - SideCopy|G1008: SideCopy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SideCopy](https://attack.mitre.org/groups/G1008) has delivered trojanized executables via spearphishing emails that contacts actor-controlled servers to download malicious payloads.(Citation: MalwareBytes SideCopy Dec 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1d2111ce-5034-472a-89a7-1818d11280fb`.
