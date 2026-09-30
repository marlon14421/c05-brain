---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0197"
target_object: "T1005"
stix_relationship_id: "relationship--145ffef4-5a63-41d7-ac74-e034e9b9622d"
---
# Relationship 3499: S0197 — uses → T1005

**Source object:** [[01 ATT&CK/S0197 - PUNCHTRACK|S0197: PUNCHTRACK]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[PUNCHTRACK](https://attack.mitre.org/software/S0197) scrapes memory for properly formatted payment card data.(Citation: FireEye Fin8 May 2016)(Citation: FireEye Know Your Enemy FIN8 Aug 2016)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--145ffef4-5a63-41d7-ac74-e034e9b9622d`.
