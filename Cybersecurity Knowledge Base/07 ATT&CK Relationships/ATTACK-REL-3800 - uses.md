---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0017"
target_object: "T1003.002"
stix_relationship_id: "relationship--4fd8f00b-2524-4c93-b49d-2f43cbe4aa5b"
---
# Relationship 3800: C0017 — uses → T1003.002

**Source object:** [[01 ATT&CK/C0017 - C0017|C0017: C0017]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1003.002 - Security Account Manager|T1003.002: Security Account Manager]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [C0017](https://attack.mitre.org/campaigns/C0017), [APT41](https://attack.mitre.org/groups/G0096) copied the `SAM` and `SYSTEM` Registry hives for credential harvesting.(Citation: Mandiant APT41)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4fd8f00b-2524-4c93-b49d-2f43cbe4aa5b`.
