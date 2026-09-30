---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1068"
target_object: "T1018"
stix_relationship_id: "relationship--25b8605b-9ab2-418f-b92b-abb2be815b90"
---
# Relationship 2998: S1068 — uses → T1018

**Source object:** [[01 ATT&CK/S1068 - BlackCat|S1068: BlackCat]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1018 - Remote System Discovery|T1018: Remote System Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BlackCat](https://attack.mitre.org/software/S1068) can broadcasts NetBIOS Name Service (NBNC) messages to search for servers connected to compromised networks.(Citation: Microsoft BlackCat Jun 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--25b8605b-9ab2-418f-b92b-abb2be815b90`.
