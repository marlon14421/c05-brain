---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9043"
target_object: "T1614.001"
stix_relationship_id: "relationship--5c316caa-ecd9-4185-bd42-16b16343d405"
---
# Relationship 3368: S9043 — uses → T1614.001

**Source object:** [[01 ATT&CK/S9043 - Mini Shai-Hulud|S9043: Mini Shai-Hulud]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1614.001 - System Language Discovery|T1614.001: System Language Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Mini Shai-Hulud](https://attack.mitre.org/software/S9043) has the ability to check system details for its language configuration and terminates actions when the system is configured for the Russian language.(Citation: Wiz Mini Shai-Hulud MAY 2026)(Citation: Phoenix TeamPCP 20 MAY 2026)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5c316caa-ecd9-4185-bd42-16b16343d405`.
