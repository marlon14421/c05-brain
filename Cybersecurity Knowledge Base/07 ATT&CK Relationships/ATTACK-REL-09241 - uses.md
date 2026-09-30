---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0527"
target_object: "T1027.002"
stix_relationship_id: "relationship--d9d86c0c-6ee9-4fdc-bb9b-6d331a44bbde"
---
# Relationship 9241: S0527 — uses → T1027.002

**Source object:** [[01 ATT&CK/S0527 - CSPY Downloader|S0527: CSPY Downloader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.002 - Software Packing|T1027.002: Software Packing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CSPY Downloader](https://attack.mitre.org/software/S0527) has been packed with UPX.(Citation: Cybereason Kimsuky November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d9d86c0c-6ee9-4fdc-bb9b-6d331a44bbde`.
