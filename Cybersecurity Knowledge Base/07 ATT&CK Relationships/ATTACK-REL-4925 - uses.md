---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0212"
target_object: "T1083"
stix_relationship_id: "relationship--a00bb928-c644-4b77-ae9c-18c3165daa00"
---
# Relationship 4925: S0212 — uses → T1083

**Source object:** [[01 ATT&CK/S0212 - CORALDECK|S0212: CORALDECK]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[CORALDECK](https://attack.mitre.org/software/S0212) searches for specified files.(Citation: FireEye APT37 Feb 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a00bb928-c644-4b77-ae9c-18c3165daa00`.
