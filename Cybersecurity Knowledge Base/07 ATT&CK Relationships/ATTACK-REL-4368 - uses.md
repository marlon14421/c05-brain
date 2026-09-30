---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0005"
target_object: "T1218.011"
stix_relationship_id: "relationship--b7f5a141-2db6-4f76-b3d7-bbd665035f84"
---
# Relationship 4368: C0005 — uses → T1218.011

**Source object:** [[01 ATT&CK/C0005 - Operation Spalax|C0005: Operation Spalax]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.011 - Rundll32|T1218.011: Rundll32]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [Operation Spalax](https://attack.mitre.org/campaigns/C0005), the threat actors used `rundll32.exe` to execute malicious installers.(Citation: ESET Operation Spalax Jan 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b7f5a141-2db6-4f76-b3d7-bbd665035f84`.
