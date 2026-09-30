---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1001"
target_object: "S1015"
stix_relationship_id: "relationship--0b0b4079-f926-4d86-9943-3074b487800c"
---
# Relationship 3178: G1001 — uses → S1015

**Source object:** [[01 ATT&CK/G1001 - HEXANE|G1001: HEXANE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S1015 - Milan|S1015: Milan]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: Kaspersky Lyceum October 2021)(Citation: Accenture Lyceum Targets November 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0b0b4079-f926-4d86-9943-3074b487800c`.
