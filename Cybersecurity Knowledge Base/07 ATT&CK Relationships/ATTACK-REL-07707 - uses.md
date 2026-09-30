---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1020"
target_object: "T1008"
stix_relationship_id: "relationship--b921077b-4a62-461c-aaec-9cd70b5cf5f8"
---
# Relationship 7707: S1020 — uses → T1008

**Source object:** [[01 ATT&CK/S1020 - Kevin|S1020: Kevin]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1008 - Fallback Channels|T1008: Fallback Channels]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kevin](https://attack.mitre.org/software/S1020) can assign hard-coded fallback domains for C2.(Citation: Kaspersky Lyceum October 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b921077b-4a62-461c-aaec-9cd70b5cf5f8`.
