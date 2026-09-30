---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0141"
target_object: "T1548.002"
stix_relationship_id: "relationship--745d3440-ecdb-4e3f-b9e6-b4484bb6c465"
---
# Relationship 3623: S0141 — uses → T1548.002

**Source object:** [[01 ATT&CK/S0141 - Winnti for Windows|S0141: Winnti for Windows]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1548.002 - Bypass User Account Control|T1548.002: Bypass User Account Control]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Winnti for Windows](https://attack.mitre.org/software/S0141) can use a variant of the sysprep UAC bypass.(Citation: Novetta Winnti April 2015)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--745d3440-ecdb-4e3f-b9e6-b4484bb6c465`.
