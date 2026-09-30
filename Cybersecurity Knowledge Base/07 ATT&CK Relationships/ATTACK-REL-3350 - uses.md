---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0102"
target_object: "T1553.002"
stix_relationship_id: "relationship--9438f268-3827-435b-98b5-79dbc0ee5213"
---
# Relationship 3350: G0102 — uses → T1553.002

**Source object:** [[01 ATT&CK/G0102 - Wizard Spider|G0102: Wizard Spider]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1553.002 - Code Signing|T1553.002: Code Signing]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Wizard Spider](https://attack.mitre.org/groups/G0102) has used Digicert code-signing certificates for some of its malware.(Citation: DFIR Ryuk 2 Hour Speed Run November 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9438f268-3827-435b-98b5-79dbc0ee5213`.
