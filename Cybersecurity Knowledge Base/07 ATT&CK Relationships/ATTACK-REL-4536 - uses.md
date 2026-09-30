---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0142"
target_object: "T1221"
stix_relationship_id: "relationship--38467bd5-4afc-4c64-b8c0-8c7140ac9e58"
---
# Relationship 4536: G0142 — uses → T1221

**Source object:** [[01 ATT&CK/G0142 - Confucius|G0142: Confucius]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1221 - Template Injection|T1221: Template Injection]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Confucius](https://attack.mitre.org/groups/G0142) has used a weaponized Microsoft Word document with an embedded RTF exploit.(Citation: Uptycs Confucius APT Jan 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--38467bd5-4afc-4c64-b8c0-8c7140ac9e58`.
