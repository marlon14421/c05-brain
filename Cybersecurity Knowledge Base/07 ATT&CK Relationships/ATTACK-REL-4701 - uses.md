---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0090"
target_object: "S0680"
stix_relationship_id: "relationship--00fd8c87-da99-42b3-a792-0d224732c84a"
---
# Relationship 4701: G0090 — uses → S0680

**Source object:** [[01 ATT&CK/G0090 - WIRTE|G0090: WIRTE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0680 - LitePower|S0680: LitePower]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: Kaspersky WIRTE November 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--00fd8c87-da99-42b3-a792-0d224732c84a`.
