---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1020"
target_object: "T1071.001"
stix_relationship_id: "relationship--92b2d8ea-6a4d-4f23-b474-ccda6fb0bfd8"
---
# Relationship 9754: S1020 — uses → T1071.001

**Source object:** [[01 ATT&CK/S1020 - Kevin|S1020: Kevin]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Variants of [Kevin](https://attack.mitre.org/software/S1020) can communicate with C2 over HTTP.(Citation: Kaspersky Lyceum October 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--92b2d8ea-6a4d-4f23-b474-ccda6fb0bfd8`.
