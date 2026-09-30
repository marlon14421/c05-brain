---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1018"
target_object: "T1608.001"
stix_relationship_id: "relationship--03b02b8a-4f47-46ef-bdda-096c214ffcda"
---
# Relationship 5983: G1018 — uses → T1608.001

**Source object:** [[01 ATT&CK/G1018 - TA2541|G1018: TA2541]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1608.001 - Upload Malware|T1608.001: Upload Malware]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TA2541](https://attack.mitre.org/groups/G1018) has uploaded malware to various platforms including Google Drive, Pastetext, Sharetext, and GitHub.(Citation: Proofpoint TA2541 February 2022)(Citation: Cisco Operation Layover September 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--03b02b8a-4f47-46ef-bdda-096c214ffcda`.
