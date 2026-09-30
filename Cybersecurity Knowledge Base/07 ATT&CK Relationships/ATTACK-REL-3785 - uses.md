---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0032"
target_object: "T1574.013"
stix_relationship_id: "relationship--c0337d13-da6a-4e2b-91a4-a389c6b4ee28"
---
# Relationship 3785: G0032 — uses → T1574.013

**Source object:** [[01 ATT&CK/G0032 - Lazarus Group|G0032: Lazarus Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1574.013 - KernelCallbackTable|T1574.013: KernelCallbackTable]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Lazarus Group](https://attack.mitre.org/groups/G0032) has abused the KernelCallbackTable to hijack process control flow and execute shellcode.(Citation: Lazarus APT January 2022)(Citation: Qualys LolZarus)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c0337d13-da6a-4e2b-91a4-a389c6b4ee28`.
