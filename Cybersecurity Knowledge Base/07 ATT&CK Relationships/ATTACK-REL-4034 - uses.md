---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1150"
target_object: "T1027.013"
stix_relationship_id: "relationship--12f96649-9314-4d5f-854b-6316737df1ed"
---
# Relationship 4034: S1150 — uses → T1027.013

**Source object:** [[01 ATT&CK/S1150 - ROADSWEEP|S1150: ROADSWEEP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

The [ROADSWEEP](https://attack.mitre.org/software/S1150) binary contains RC4 encrypted embedded scripts.(Citation: Mandiant ROADSWEEP August 2022)(Citation: CISA Iran Albanian Attacks September 2022)(Citation: Microsoft Albanian Government Attacks September 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--12f96649-9314-4d5f-854b-6316737df1ed`.
