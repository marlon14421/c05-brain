---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0501"
target_object: "T1082"
stix_relationship_id: "relationship--270c93ba-a3d4-4ace-8fad-691c64c13e2f"
---
# Relationship 3325: S0501 — uses → T1082

**Source object:** [[01 ATT&CK/S0501 - PipeMon|S0501: PipeMon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[PipeMon](https://attack.mitre.org/software/S0501) can collect and send OS version and computer name as a part of its C2 beacon.(Citation: ESET PipeMon May 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--270c93ba-a3d4-4ace-8fad-691c64c13e2f`.
