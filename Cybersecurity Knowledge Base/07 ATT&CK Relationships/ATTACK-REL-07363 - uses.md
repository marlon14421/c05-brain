---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0547"
target_object: "T1083"
stix_relationship_id: "relationship--4a358258-d616-4f15-aead-d4e6f6153aae"
---
# Relationship 7363: S0547 — uses → T1083

**Source object:** [[01 ATT&CK/S0547 - DropBook|S0547: DropBook]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DropBook](https://attack.mitre.org/software/S0547) can collect the names of all files and folders in the Program Files directories.(Citation: Cybereason Molerats Dec 2020)(Citation: BleepingComputer Molerats Dec 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4a358258-d616-4f15-aead-d4e6f6153aae`.
