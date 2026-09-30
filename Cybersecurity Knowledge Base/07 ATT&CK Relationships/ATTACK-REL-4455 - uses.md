---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0130"
target_object: "S0225"
stix_relationship_id: "relationship--03632545-0422-4b88-b5c8-f3b52ccfd28f"
---
# Relationship 4455: G0130 — uses → S0225

**Source object:** [[01 ATT&CK/G0130 - Ajax Security Team|G0130: Ajax Security Team]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0225 - sqlmap|S0225: sqlmap]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: Check Point Rocket Kitten)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--03632545-0422-4b88-b5c8-f3b52ccfd28f`.
