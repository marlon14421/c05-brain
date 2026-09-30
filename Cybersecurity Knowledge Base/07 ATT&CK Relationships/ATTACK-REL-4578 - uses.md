---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1078"
target_object: "T1546.004"
stix_relationship_id: "relationship--226961a0-998c-4402-a7de-3c7922c4b45e"
---
# Relationship 4578: S1078 — uses → T1546.004

**Source object:** [[01 ATT&CK/S1078 - RotaJakiro|S1078: RotaJakiro]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1546.004 - Unix Shell Configuration Modification|T1546.004: Unix Shell Configuration Modification]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

When executing with non-root level permissions, [RotaJakiro](https://attack.mitre.org/software/S1078) can install persistence by adding a command to the .bashrc file that executes a binary in the `${HOME}/.gvfsd/.profile/` folder.(Citation: RotaJakiro 2021 netlab360 analysis)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--226961a0-998c-4402-a7de-3c7922c4b45e`.
