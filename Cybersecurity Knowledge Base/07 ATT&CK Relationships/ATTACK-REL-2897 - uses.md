---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0588"
target_object: "T1053.003"
stix_relationship_id: "relationship--67f336eb-31e7-4904-9ed4-07ca68cd3838"
---
# Relationship 2897: S0588 — uses → T1053.003

**Source object:** [[01 ATT&CK/S0588 - GoldMax|S0588: GoldMax]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.003 - Cron|T1053.003: Cron]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

The [GoldMax](https://attack.mitre.org/software/S0588) Linux variant has used a crontab entry with a @reboot line to gain persistence.(Citation: CrowdStrike StellarParticle January 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--67f336eb-31e7-4904-9ed4-07ca68cd3838`.
