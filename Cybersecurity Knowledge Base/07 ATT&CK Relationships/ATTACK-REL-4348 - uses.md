---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0094"
target_object: "T1082"
stix_relationship_id: "relationship--96a9cf17-42b0-4317-82e6-55e42a2dab41"
---
# Relationship 4348: G0094 — uses → T1082

**Source object:** [[01 ATT&CK/G0094 - Kimsuky|G0094: Kimsuky]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Kimsuky](https://attack.mitre.org/groups/G0094) has enumerated OS type, OS version, and other information using a script or the "systeminfo" command.(Citation: Securelist Kimsuky Sept 2013)(Citation: Talos Kimsuky Nov 2021) [Kimsuky](https://attack.mitre.org/groups/G0094) has also obtained system information such as OS type, OS version, and system type through querying various Windows Management Instrumentation (WMI) classes including `Win32_OperatingSystem`.(Citation: Securonix Kimsuky February 2025)(Citation: Aryaka Kimsuky July 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--96a9cf17-42b0-4317-82e6-55e42a2dab41`.
