---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0013"
target_object: "T1036.004"
stix_relationship_id: "relationship--0d989c2e-0207-4412-b52a-5d9bf9f96d18"
---
# Relationship 7849: S0013 — uses → T1036.004

**Source object:** [[01 ATT&CK/S0013 - PlugX|S0013: PlugX]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.004 - Masquerade Task or Service|T1036.004: Masquerade Task or Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

In one instance, [menuPass](https://attack.mitre.org/groups/G0045) added [PlugX](https://attack.mitre.org/software/S0013) as a service with a display name of "Corel Writing Tools Utility."(Citation: FireEye APT10 April 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0d989c2e-0207-4412-b52a-5d9bf9f96d18`.
