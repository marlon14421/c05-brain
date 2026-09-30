---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0605"
target_object: "T1486"
stix_relationship_id: "relationship--36106fcd-5f7f-47b9-8a45-1faa89d2ba36"
---
# Relationship 4940: S0605 — uses → T1486

**Source object:** [[01 ATT&CK/S0605 - EKANS|S0605: EKANS]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1486 - Data Encrypted for Impact|T1486: Data Encrypted for Impact]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[EKANS](https://attack.mitre.org/software/S0605) uses standard encryption library functions to encrypt files.(Citation: Dragos EKANS)(Citation: Palo Alto Unit 42 EKANS)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--36106fcd-5f7f-47b9-8a45-1faa89d2ba36`.
