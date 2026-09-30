---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0045"
target_object: "S0404"
stix_relationship_id: "relationship--d608c524-ad0a-4595-8fe2-4a0ec0dbf501"
---
# Relationship 4933: G0045 — uses → S0404

**Source object:** [[01 ATT&CK/G0045 - menuPass|G0045: menuPass]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0404 - esentutl|S0404: esentutl]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: FireEye APT10 Sept 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d608c524-ad0a-4595-8fe2-4a0ec0dbf501`.
