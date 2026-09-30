---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0493"
target_object: "T1083"
stix_relationship_id: "relationship--7f499274-44b7-4415-a8e8-6b2134a7873e"
---
# Relationship 5096: S0493 — uses → T1083

**Source object:** [[01 ATT&CK/S0493 - GoldenSpy|S0493: GoldenSpy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[GoldenSpy](https://attack.mitre.org/software/S0493) has included a program "ExeProtector", which monitors for the existence of [GoldenSpy](https://attack.mitre.org/software/S0493) on the infected system and redownloads if necessary.(Citation: Trustwave GoldenSpy June 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7f499274-44b7-4415-a8e8-6b2134a7873e`.
