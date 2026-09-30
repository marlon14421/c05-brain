---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0002"
target_object: "T1003.002"
stix_relationship_id: "relationship--791d8691-7e06-4052-8c49-1a9f57ccf09d"
---
# Relationship 4856: C0002 — uses → T1003.002

**Source object:** [[01 ATT&CK/C0002 - Night Dragon|C0002: Night Dragon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1003.002 - Security Account Manager|T1003.002: Security Account Manager]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [Night Dragon](https://attack.mitre.org/campaigns/C0002), threat actors dumped account hashes using [gsecdump](https://attack.mitre.org/software/S0008).(Citation: McAfee Night Dragon)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--791d8691-7e06-4052-8c49-1a9f57ccf09d`.
