---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1033"
target_object: "T1684.001"
stix_relationship_id: "relationship--006e52ca-80ac-458a-943e-0595f570fe73"
---
# Relationship 8599: G1033 — uses → T1684.001

**Source object:** [[01 ATT&CK/G1033 - Star Blizzard|G1033: Star Blizzard]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1684.001 - Impersonation|T1684.001: Impersonation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Star Blizzard](https://attack.mitre.org/groups/G1033) has registered impersonation email accounts to spoof experts in a particular field or individuals and organizations affiliated with the intended target.(Citation: Microsoft Star Blizzard August 2022)(Citation: CISA Star Blizzard Advisory December 2023)(Citation: Google TAG COLDRIVER January 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--006e52ca-80ac-458a-943e-0595f570fe73`.
