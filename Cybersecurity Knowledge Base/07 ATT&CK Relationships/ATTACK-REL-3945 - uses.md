---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0663"
target_object: "T1027.011"
stix_relationship_id: "relationship--596099b1-11a9-43c3-ae21-d5a31233e5c2"
---
# Relationship 3945: S0663 — uses → T1027.011

**Source object:** [[01 ATT&CK/S0663 - SysUpdate|S0663: SysUpdate]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.011 - Fileless Storage|T1027.011: Fileless Storage]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SysUpdate](https://attack.mitre.org/software/S0663) can store its encoded configuration file within Software\Classes\scConfig in either HKEY_LOCAL_MACHINE or HKEY_CURRENT_USER .(Citation: Trend Micro Iron Tiger April 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--596099b1-11a9-43c3-ae21-d5a31233e5c2`.
