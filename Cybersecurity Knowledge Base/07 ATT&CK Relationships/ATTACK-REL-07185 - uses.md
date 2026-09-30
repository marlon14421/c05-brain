---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1183"
target_object: "T1119"
stix_relationship_id: "relationship--ef704a2d-c73c-4cf1-947d-f70efbee6894"
---
# Relationship 7185: S1183 — uses → T1119

**Source object:** [[01 ATT&CK/S1183 - StrelaStealer|S1183: StrelaStealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1119 - Automated Collection|T1119: Automated Collection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[StrelaStealer](https://attack.mitre.org/software/S1183) attempts to identify and collect mail login data from Thunderbird and Outlook following execution.(Citation: DCSO StrelaStealer 2022)(Citation: PaloAlto StrelaStealer 2024)(Citation: Fortgale StrelaStealer 2023)(Citation: IBM StrelaStealer 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ef704a2d-c73c-4cf1-947d-f70efbee6894`.
