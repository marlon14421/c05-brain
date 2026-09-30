---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0368"
target_object: "T1003.001"
stix_relationship_id: "relationship--7cfb528c-6c2d-4f67-b59e-c343678db839"
---
# Relationship 6851: S0368 — uses → T1003.001

**Source object:** [[01 ATT&CK/S0368 - NotPetya|S0368: NotPetya]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1003.001 - LSASS Memory|T1003.001: LSASS Memory]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[NotPetya](https://attack.mitre.org/software/S0368) contains a modified version of [Mimikatz](https://attack.mitre.org/software/S0002) to help gather credentials that are later used for lateral movement.(Citation: Talos Nyetya June 2017)(Citation: US-CERT NotPetya 2017)(Citation: NCSC Joint Report Public Tools)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7cfb528c-6c2d-4f67-b59e-c343678db839`.
