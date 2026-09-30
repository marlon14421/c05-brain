---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0438"
target_object: "T1083"
stix_relationship_id: "relationship--01a01a28-19e5-4e32-8a24-a98f2b69ced5"
---
# Relationship 4466: S0438 — uses → T1083

**Source object:** [[01 ATT&CK/S0438 - Attor|S0438: Attor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Attor](https://attack.mitre.org/software/S0438) has a plugin that enumerates files with specific extensions on all hard disk drives and stores file information in encrypted log files.(Citation: ESET Attor Oct 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--01a01a28-19e5-4e32-8a24-a98f2b69ced5`.
