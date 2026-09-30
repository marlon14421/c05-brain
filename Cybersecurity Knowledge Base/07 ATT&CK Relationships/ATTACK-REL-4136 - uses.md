---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1097"
target_object: "T1685"
stix_relationship_id: "relationship--b8f09e6e-b9f6-443e-8ac8-9cc69940f740"
---
# Relationship 4136: S1097 — uses → T1685

**Source object:** [[01 ATT&CK/S1097 - HUI Loader|S1097: HUI Loader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1685 - Disable or Modify Tools|T1685: Disable or Modify Tools]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[HUI Loader](https://attack.mitre.org/software/S1097) has the ability to disable Windows Event Tracing for Windows (ETW) and Antimalware Scan Interface (AMSI) functions.(Citation: SecureWorks BRONZE STARLIGHT Ransomware Operations June 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b8f09e6e-b9f6-443e-8ac8-9cc69940f740`.
