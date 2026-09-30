---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0254"
target_object: "T1082"
stix_relationship_id: "relationship--072af62a-85d5-4803-aa05-d7c6efa9ec2a"
---
# Relationship 2934: S0254 — uses → T1082

**Source object:** [[01 ATT&CK/S0254 - PLAINTEE|S0254: PLAINTEE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[PLAINTEE](https://attack.mitre.org/software/S0254) collects general system enumeration data about the infected machine and checks the OS version.(Citation: Rancor Unit42 June 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--072af62a-85d5-4803-aa05-d7c6efa9ec2a`.
