---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0087"
target_object: "T1110"
stix_relationship_id: "relationship--c4a566d6-69ce-4284-809d-433663e3e2fa"
---
# Relationship 4703: G0087 — uses → T1110

**Source object:** [[01 ATT&CK/G0087 - APT39|G0087: APT39]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1110 - Brute Force|T1110: Brute Force]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[APT39](https://attack.mitre.org/groups/G0087) has used Ncrack to reveal credentials.(Citation: FireEye APT39 Jan 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c4a566d6-69ce-4284-809d-433663e3e2fa`.
