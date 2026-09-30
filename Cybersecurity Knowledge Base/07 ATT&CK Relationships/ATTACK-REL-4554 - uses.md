---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0117"
target_object: "S0029"
stix_relationship_id: "relationship--d9a97894-9a90-43cd-b9b9-9d13545aeb5a"
---
# Relationship 4554: G0117 — uses → S0029

**Source object:** [[01 ATT&CK/G0117 - Fox Kitten|G0117: Fox Kitten]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0029 - PsExec|S0029: PsExec]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: CISA AA20-259A Iran-Based Actor September 2020)(Citation: Check Point Pay2Key November 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d9a97894-9a90-43cd-b9b9-9d13545aeb5a`.
