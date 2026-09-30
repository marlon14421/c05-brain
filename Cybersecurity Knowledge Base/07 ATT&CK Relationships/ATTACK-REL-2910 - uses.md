---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0336"
target_object: "T1547.001"
stix_relationship_id: "relationship--dd417d31-d129-44ac-8a9f-b14b79235dfa"
---
# Relationship 2910: S0336 — uses → T1547.001

**Source object:** [[01 ATT&CK/S0336 - NanoCore|S0336: NanoCore]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[NanoCore](https://attack.mitre.org/software/S0336) creates a RunOnce key in the Registry to execute its VBS scripts each time the user logs on to the machine.(Citation: Cofense NanoCore Mar 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dd417d31-d129-44ac-8a9f-b14b79235dfa`.
