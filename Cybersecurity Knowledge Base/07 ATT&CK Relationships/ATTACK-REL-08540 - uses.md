---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0590"
target_object: "T1018"
stix_relationship_id: "relationship--be8fb0e9-a924-47be-9bb6-1eebe05881b7"
---
# Relationship 8540: S0590 — uses → T1018

**Source object:** [[01 ATT&CK/S0590 - NBTscan|S0590: NBTscan]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1018 - Remote System Discovery|T1018: Remote System Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[NBTscan](https://attack.mitre.org/software/S0590) can list NetBIOS computer names.(Citation: Debian nbtscan Nov 2019)(Citation: SecTools nbtscan June 2003)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--be8fb0e9-a924-47be-9bb6-1eebe05881b7`.
