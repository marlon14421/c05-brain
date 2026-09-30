---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0081"
target_object: "T1132.001"
stix_relationship_id: "relationship--91180074-16cd-448f-8955-628d06965e22"
---
# Relationship 3752: G0081 — uses → T1132.001

**Source object:** [[01 ATT&CK/G0081 - Tropic Trooper|G0081: Tropic Trooper]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1132.001 - Standard Encoding|T1132.001: Standard Encoding]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Tropic Trooper](https://attack.mitre.org/groups/G0081) has used base64 encoding to hide command strings delivered from the C2.(Citation: TrendMicro Tropic Trooper May 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--91180074-16cd-448f-8955-628d06965e22`.
