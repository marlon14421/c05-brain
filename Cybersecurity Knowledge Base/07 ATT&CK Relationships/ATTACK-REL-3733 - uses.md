---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0018"
target_object: "S0154"
stix_relationship_id: "relationship--aea03b1a-38b1-423c-8dc0-442bb4d6c316"
---
# Relationship 3733: C0018 — uses → S0154

**Source object:** [[01 ATT&CK/C0018 - C0018|C0018: C0018]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0154 - Cobalt Strike|S0154: Cobalt Strike]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: Cisco Talos Avos Jun 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--aea03b1a-38b1-423c-8dc0-442bb4d6c316`.
