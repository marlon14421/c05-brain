---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0032"
target_object: "S0584"
stix_relationship_id: "relationship--d0076185-9619-4365-b74a-44f52cc92c79"
---
# Relationship 4309: G0032 — uses → S0584

**Source object:** [[01 ATT&CK/G0032 - Lazarus Group|G0032: Lazarus Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0584 - AppleJeus|S0584: AppleJeus]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: CISA AppleJeus Feb 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d0076185-9619-4365-b74a-44f52cc92c79`.
