---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0667"
target_object: "T1560"
stix_relationship_id: "relationship--02174a5c-9cda-4ddc-9952-1ff1b956d31e"
---
# Relationship 2648: S0667 — uses → T1560

**Source object:** [[01 ATT&CK/S0667 - Chrommme|S0667: Chrommme]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1560 - Archive Collected Data|T1560: Archive Collected Data]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Chrommme](https://attack.mitre.org/software/S0667) can encrypt and store on disk collected data before exfiltration.(Citation: ESET Gelsemium June 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--02174a5c-9cda-4ddc-9952-1ff1b956d31e`.
