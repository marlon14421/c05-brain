---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0667"
target_object: "T1005"
stix_relationship_id: "relationship--da542c01-9b62-4e42-9036-809ceb31eb8d"
---
# Relationship 2667: S0667 — uses → T1005

**Source object:** [[01 ATT&CK/S0667 - Chrommme|S0667: Chrommme]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Chrommme](https://attack.mitre.org/software/S0667) can collect data from a local system.(Citation: ESET Gelsemium June 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--da542c01-9b62-4e42-9036-809ceb31eb8d`.
