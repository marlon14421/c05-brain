---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0279"
target_object: "T1070.004"
stix_relationship_id: "relationship--1f8760c6-f11c-43f7-acf8-bc30a347518c"
---
# Relationship 3691: S0279 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0279 - Proton|S0279: Proton]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Proton](https://attack.mitre.org/software/S0279) removes all files in the /tmp directory.(Citation: objsee mac malware 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1f8760c6-f11c-43f7-acf8-bc30a347518c`.
