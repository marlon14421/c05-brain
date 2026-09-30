---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0137"
target_object: "T1036.002"
stix_relationship_id: "relationship--54501ca8-7205-4b83-87cb-b2235bc0ec71"
---
# Relationship 4043: G0137 — uses → T1036.002

**Source object:** [[01 ATT&CK/G0137 - Ferocious Kitten|G0137: Ferocious Kitten]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.002 - Right-to-Left Override|T1036.002: Right-to-Left Override]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Ferocious Kitten](https://attack.mitre.org/groups/G0137) has used right-to-left override to reverse executables’ names to make them appear to have different file extensions, rather than their real ones.(Citation: Kaspersky Ferocious Kitten Jun 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--54501ca8-7205-4b83-87cb-b2235bc0ec71`.
