---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0170"
target_object: "T1069.002"
stix_relationship_id: "relationship--c2541365-58bd-474c-82ab-28c7b63e7fb8"
---
# Relationship 3144: S0170 — uses → T1069.002

**Source object:** [[01 ATT&CK/S0170 - Helminth|S0170: Helminth]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1069.002 - Domain Groups|T1069.002: Domain Groups]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Helminth](https://attack.mitre.org/software/S0170) has checked for the domain admin group and Exchange Trusted Subsystem groups using the commands net group Exchange Trusted Subsystem /domain and net group domain admins /domain .(Citation: Unit 42 Playbook Dec 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c2541365-58bd-474c-82ab-28c7b63e7fb8`.
