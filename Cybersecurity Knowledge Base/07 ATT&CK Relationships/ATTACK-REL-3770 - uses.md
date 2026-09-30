---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0683"
target_object: "T1078.004"
stix_relationship_id: "relationship--c37d24cf-8ea8-4212-831e-bc3f37c10893"
---
# Relationship 3770: S0683 — uses → T1078.004

**Source object:** [[01 ATT&CK/S0683 - Peirates|S0683: Peirates]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1078.004 - Cloud Accounts|T1078.004: Cloud Accounts]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Peirates](https://attack.mitre.org/software/S0683) can use stolen service account tokens to perform its operations.(Citation: Peirates GitHub)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c37d24cf-8ea8-4212-831e-bc3f37c10893`.
