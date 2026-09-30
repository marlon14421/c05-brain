---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1156"
target_object: "T1082"
stix_relationship_id: "relationship--0fa5e3ed-8b00-4f03-9adf-caf5d0e0bd2c"
---
# Relationship 2698: S1156 — uses → T1082

**Source object:** [[01 ATT&CK/S1156 - Manjusaka|S1156: Manjusaka]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Manjusaka](https://attack.mitre.org/software/S1156) performs basic system profiling actions to fingerprint and register the victim system with the C2 controller.(Citation: Talos Manjusaka 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0fa5e3ed-8b00-4f03-9adf-caf5d0e0bd2c`.
