---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0667"
target_object: "T1027.013"
stix_relationship_id: "relationship--86c83427-c35b-46c2-9c55-90b1967bed49"
---
# Relationship 4324: S0667 — uses → T1027.013

**Source object:** [[01 ATT&CK/S0667 - Chrommme|S0667: Chrommme]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Chrommme](https://attack.mitre.org/software/S0667) can encrypt sections of its code to evade detection.(Citation: ESET Gelsemium June 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--86c83427-c35b-46c2-9c55-90b1967bed49`.
