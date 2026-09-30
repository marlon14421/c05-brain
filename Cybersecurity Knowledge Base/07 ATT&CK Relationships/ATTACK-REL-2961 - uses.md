---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0027"
target_object: "T1003.001"
stix_relationship_id: "relationship--21f2fd40-073c-4c25-bf4e-19339ac1f99d"
---
# Relationship 2961: G0027 — uses → T1003.001

**Source object:** [[01 ATT&CK/G0027 - Threat Group-3390|G0027: Threat Group-3390]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1003.001 - LSASS Memory|T1003.001: LSASS Memory]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Threat Group-3390](https://attack.mitre.org/groups/G0027) actors have used a modified version of [Mimikatz](https://attack.mitre.org/software/S0002) called Wrapikatz to dump credentials. They have also dumped credentials from domain controllers.(Citation: Dell TG-3390)(Citation: SecureWorks BRONZE UNION June 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--21f2fd40-073c-4c25-bf4e-19339ac1f99d`.
