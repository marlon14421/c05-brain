---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1212"
target_object: "T1490"
stix_relationship_id: "relationship--999097f3-7fe8-425f-a9cc-81ee310e05f1"
---
# Relationship 2877: S1212 — uses → T1490

**Source object:** [[01 ATT&CK/S1212 - RansomHub|S1212: RansomHub]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1490 - Inhibit System Recovery|T1490: Inhibit System Recovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[RansomHub](https://attack.mitre.org/software/S1212) has used `vssadmin.exe` to delete volume shadow copies.(Citation: CISA RansomHub AUG 2024)(Citation: Group-IB RansomHub FEB 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--999097f3-7fe8-425f-a9cc-81ee310e05f1`.
