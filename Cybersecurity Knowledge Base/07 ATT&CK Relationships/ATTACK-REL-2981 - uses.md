---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1234"
target_object: "T1106"
stix_relationship_id: "relationship--cd518b36-513f-44d8-b7c9-7462fe5b3902"
---
# Relationship 2981: S1234 — uses → T1106

**Source object:** [[01 ATT&CK/S1234 - SplatCloak|S1234: SplatCloak]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SplatCloak](https://attack.mitre.org/software/S1234) has utilized Native Windows API calls dynamically through `ZwQuerySystemInformation`.(Citation: Zscaler PAKLOG CorkLog SplatCloak Splatdropper April 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cd518b36-513f-44d8-b7c9-7462fe5b3902`.
