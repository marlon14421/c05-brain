---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1164"
target_object: "T1036"
stix_relationship_id: "relationship--99bc173b-a825-483c-969e-868356209ff6"
---
# Relationship 2940: S1164 — uses → T1036

**Source object:** [[01 ATT&CK/S1164 - UPSTYLE|S1164: UPSTYLE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036 - Masquerading|T1036: Masquerading]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[UPSTYLE](https://attack.mitre.org/software/S1164) has masqueraded filenames using examples such as `update.py`.(Citation: Volexity UPSTYLE 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--99bc173b-a825-483c-969e-868356209ff6`.
