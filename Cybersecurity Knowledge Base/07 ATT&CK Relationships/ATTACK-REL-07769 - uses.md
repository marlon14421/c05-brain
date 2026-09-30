---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0481"
target_object: "T1564.006"
stix_relationship_id: "relationship--913c67d5-0c5b-40d5-be88-6ce4e5030603"
---
# Relationship 7769: S0481 — uses → T1564.006

**Source object:** [[01 ATT&CK/S0481 - Ragnar Locker|S0481: Ragnar Locker]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.006 - Run Virtual Instance|T1564.006: Run Virtual Instance]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Ragnar Locker](https://attack.mitre.org/software/S0481) has used VirtualBox and a stripped Windows XP virtual machine to run itself. The use of a shared folder specified in the configuration enables [Ragnar Locker](https://attack.mitre.org/software/S0481) to encrypt files on the host operating system, including files on any mapped drives.(Citation: Sophos Ragnar May 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--913c67d5-0c5b-40d5-be88-6ce4e5030603`.
