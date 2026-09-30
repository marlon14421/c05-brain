---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1230"
target_object: "T1091"
stix_relationship_id: "relationship--155b3e76-eaf8-4b4c-95b6-7836a6c81f76"
---
# Relationship 3334: S1230 — uses → T1091

**Source object:** [[01 ATT&CK/S1230 - HIUPAN|S1230: HIUPAN]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1091 - Replication Through Removable Media|T1091: Replication Through Removable Media]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[HIUPAN](https://attack.mitre.org/software/S1230) has periodically checked for removable and hot-plugged drives connected to the infected machine, should one be found [HIUPAN](https://attack.mitre.org/software/S1230) will propagate to the removeable drives by copying itself and accompanying malware components to a directory to the new drive in a hidden subdirectory ` :\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\` and hides any other existing files to ensure UsbConfig.exe is the only visible file on the device.(Citation: 2025_IBM_PUBLOAD_TONESHELL_HIUPAN_CLAIMLOADER_MUSTANG PANDA)(Citation: Trend Micro MUSTANG PANDA PUBLOAD HIUPAN SEPTEMBER 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--155b3e76-eaf8-4b4c-95b6-7836a6c81f76`.
