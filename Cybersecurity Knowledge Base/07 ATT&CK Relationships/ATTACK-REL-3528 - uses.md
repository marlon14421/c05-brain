---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0125"
target_object: "T1033"
stix_relationship_id: "relationship--d1222ff7-b93c-40a7-99bd-217d795d8d58"
---
# Relationship 3528: S0125 — uses → T1033

**Source object:** [[01 ATT&CK/S0125 - Remsec|S0125: Remsec]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Remsec](https://attack.mitre.org/software/S0125) can obtain information about the current user.(Citation: Kaspersky ProjectSauron Technical Analysis)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d1222ff7-b93c-40a7-99bd-217d795d8d58`.
