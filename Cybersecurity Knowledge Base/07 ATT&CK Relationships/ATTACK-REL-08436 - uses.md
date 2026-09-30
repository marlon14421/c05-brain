---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0096"
target_object: "S0013"
stix_relationship_id: "relationship--22af1cbd-a7fd-4d9f-ba15-d640c217603e"
---
# Relationship 8436: G0096 — uses → S0013

**Source object:** [[01 ATT&CK/G0096 - APT41|G0096: APT41]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0013 - PlugX|S0013: PlugX]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT41](https://attack.mitre.org/groups/G0096) used a variant of [PlugX](https://attack.mitre.org/software/S0013) to connect to Windows and Linux systems via SSH and Samba/CIFS.(Citation: apt41_mandiant)(Citation: FireEye APT41 Aug 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--22af1cbd-a7fd-4d9f-ba15-d640c217603e`.
