---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0618"
target_object: "T1083"
stix_relationship_id: "relationship--66b5808f-b124-4736-bb6b-289503d07fa2"
---
# Relationship 9024: S0618 — uses → T1083

**Source object:** [[01 ATT&CK/S0618 - FIVEHANDS|S0618: FIVEHANDS]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FIVEHANDS](https://attack.mitre.org/software/S0618) has the ability to enumerate files on a compromised host in order to encrypt files with specific extensions.(Citation: CISA AR21-126A FIVEHANDS May 2021)(Citation: NCC Group Fivehands June 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--66b5808f-b124-4736-bb6b-289503d07fa2`.
