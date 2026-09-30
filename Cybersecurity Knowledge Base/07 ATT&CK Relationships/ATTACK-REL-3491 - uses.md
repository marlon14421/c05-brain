---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0447"
target_object: "T1564.001"
stix_relationship_id: "relationship--af1fc367-9987-4076-9ce6-2414cd2d4a1f"
---
# Relationship 3491: S0447 — uses → T1564.001

**Source object:** [[01 ATT&CK/S0447 - Lokibot|S0447: Lokibot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.001 - Hidden Files and Directories|T1564.001: Hidden Files and Directories]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Lokibot](https://attack.mitre.org/software/S0447) has the ability to copy itself to a hidden file and directory.(Citation: Infoblox Lokibot January 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--af1fc367-9987-4076-9ce6-2414cd2d4a1f`.
