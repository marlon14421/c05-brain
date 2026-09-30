---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0140"
target_object: "T1218.005"
stix_relationship_id: "relationship--3766cf55-568a-410f-8968-7a4adac96f77"
---
# Relationship 3337: G0140 — uses → T1218.005

**Source object:** [[01 ATT&CK/G0140 - LazyScripter|G0140: LazyScripter]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.005 - Mshta|T1218.005: Mshta]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[LazyScripter](https://attack.mitre.org/groups/G0140) has used `mshta.exe` to execute [Koadic](https://attack.mitre.org/software/S0250) stagers.(Citation: MalwareBytes LazyScripter Feb 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3766cf55-568a-410f-8968-7a4adac96f77`.
