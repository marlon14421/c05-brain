---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0590"
target_object: "T1033"
stix_relationship_id: "relationship--06711c3f-230b-4d44-9c88-4861c48d2716"
---
# Relationship 9786: S0590 — uses → T1033

**Source object:** [[01 ATT&CK/S0590 - NBTscan|S0590: NBTscan]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[NBTscan](https://attack.mitre.org/software/S0590) can list active users on the system.(Citation: Debian nbtscan Nov 2019)(Citation: SecTools nbtscan June 2003)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--06711c3f-230b-4d44-9c88-4861c48d2716`.
