---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0274"
target_object: "T1136.001"
stix_relationship_id: "relationship--fe99ee01-a049-4867-bf3b-27d05461b0b3"
---
# Relationship 2749: S0274 — uses → T1136.001

**Source object:** [[01 ATT&CK/S0274 - Calisto|S0274: Calisto]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1136.001 - Local Account|T1136.001: Local Account]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Calisto](https://attack.mitre.org/software/S0274) has the capability to add its own account to the victim's machine.(Citation: Symantec Calisto July 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fe99ee01-a049-4867-bf3b-27d05461b0b3`.
