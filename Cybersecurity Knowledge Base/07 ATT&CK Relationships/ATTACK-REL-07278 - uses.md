---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0007"
target_object: "T1092"
stix_relationship_id: "relationship--c569059f-8a7d-4777-a111-d3ab62d178ca"
---
# Relationship 7278: G0007 — uses → T1092

**Source object:** [[01 ATT&CK/G0007 - APT28|G0007: APT28]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1092 - Communication Through Removable Media|T1092: Communication Through Removable Media]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT28](https://attack.mitre.org/groups/G0007) uses a tool that captures information from air-gapped computers via an infected USB and transfers it to network-connected computer when the USB is inserted.(Citation: Microsoft SIR Vol 19)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c569059f-8a7d-4777-a111-d3ab62d178ca`.
