---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "attributed-to"
source_object: "C0040"
target_object: "G0096"
stix_relationship_id: "relationship--31aebdb8-ce4d-4d31-a144-7a5c354bfd7c"
---
# Relationship 2632: C0040 — attributed-to → G0096

**Source object:** [[01 ATT&CK/C0040 - APT41 DUST|C0040: APT41 DUST]]  
**Relationship:** `attributed-to`  
**Target object:** [[01 ATT&CK/G0096 - APT41|G0096: APT41]]

## Meaning for defensive analysis

Records an attribution relationship in the source catalog; attribution is probabilistic and should not be treated as certainty.

## Source description

[APT41 DUST](https://attack.mitre.org/campaigns/C0040) was conducted by [APT41](https://attack.mitre.org/groups/G0096) from 2023 to July 2024.(Citation: Google Cloud APT41 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--31aebdb8-ce4d-4d31-a144-7a5c354bfd7c`.
