---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0046"
target_object: "T1195.002"
stix_relationship_id: "relationship--e814521c-211d-4db9-b637-dd13ccdfed92"
---
# Relationship 4205: G0046 — uses → T1195.002

**Source object:** [[01 ATT&CK/G0046 - FIN7|G0046: FIN7]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1195.002 - Compromise Software Supply Chain|T1195.002: Compromise Software Supply Chain]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[FIN7](https://attack.mitre.org/groups/G0046) has gained initial access by compromising a victim's software supply chain.(Citation: Mandiant FIN7 Apr 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e814521c-211d-4db9-b637-dd13ccdfed92`.
