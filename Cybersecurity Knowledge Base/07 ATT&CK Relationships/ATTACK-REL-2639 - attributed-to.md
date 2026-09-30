---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "attributed-to"
source_object: "C0049"
target_object: "G0065"
stix_relationship_id: "relationship--920874f2-f1e1-4981-9469-4ee45b6218a7"
---
# Relationship 2639: C0049 — attributed-to → G0065

**Source object:** [[01 ATT&CK/C0049 - Leviathan Australian Intrusions|C0049: Leviathan Australian Intrusions]]  
**Relationship:** `attributed-to`  
**Target object:** [[01 ATT&CK/G0065 - Leviathan|G0065: Leviathan]]

## Meaning for defensive analysis

Records an attribution relationship in the source catalog; attribution is probabilistic and should not be treated as certainty.

## Source description

[Leviathan Australian Intrusions](https://attack.mitre.org/campaigns/C0049) was conducted by the [Leviathan](https://attack.mitre.org/groups/G0065) threat actor.(Citation: CISA Leviathan 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--920874f2-f1e1-4981-9469-4ee45b6218a7`.
