---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0096"
target_object: "S0160"
stix_relationship_id: "relationship--9cdb5a1a-a68f-4ee2-a807-ba4c0ae8e436"
---
# Relationship 4633: G0096 — uses → S0160

**Source object:** [[01 ATT&CK/G0096 - APT41|G0096: APT41]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0160 - certutil|S0160: certutil]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: FireEye APT41 March 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9cdb5a1a-a68f-4ee2-a807-ba4c0ae8e436`.
