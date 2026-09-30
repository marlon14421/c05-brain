---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0081"
target_object: "T1091"
stix_relationship_id: "relationship--fded4f08-6cb0-4259-a6a9-f0d62537164f"
---
# Relationship 9705: G0081 — uses → T1091

**Source object:** [[01 ATT&CK/G0081 - Tropic Trooper|G0081: Tropic Trooper]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1091 - Replication Through Removable Media|T1091: Replication Through Removable Media]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Tropic Trooper](https://attack.mitre.org/groups/G0081) has attempted to transfer [USBferry](https://attack.mitre.org/software/S0452) from an infected USB device by copying an Autorun function to the target machine.(Citation: TrendMicro Tropic Trooper May 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fded4f08-6cb0-4259-a6a9-f0d62537164f`.
