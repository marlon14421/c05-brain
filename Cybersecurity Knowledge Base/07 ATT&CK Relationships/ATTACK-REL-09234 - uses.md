---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1122"
target_object: "T1056.002"
stix_relationship_id: "relationship--aa6411df-8f39-4368-9b35-45cc2a7394d8"
---
# Relationship 9234: S1122 — uses → T1056.002

**Source object:** [[01 ATT&CK/S1122 - Mispadu|S1122: Mispadu]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.002 - GUI Input Capture|T1056.002: GUI Input Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mispadu](https://attack.mitre.org/software/S1122) can monitor browser activity for online banking actions and display full-screen overlay images to block user access to the intended site or present additional data fields.(Citation: Segurança Informática URSA Sophisticated Loader 2020)(Citation: SCILabs Malteiro 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--aa6411df-8f39-4368-9b35-45cc2a7394d8`.
