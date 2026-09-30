---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0649"
target_object: "T1573.001"
stix_relationship_id: "relationship--0335dd7e-1f5e-4068-b680-197de6c0af68"
---
# Relationship 3433: S0649 — uses → T1573.001

**Source object:** [[01 ATT&CK/S0649 - SMOKEDHAM|S0649: SMOKEDHAM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SMOKEDHAM](https://attack.mitre.org/software/S0649) has encrypted its C2 traffic with RC4.(Citation: FireEye SMOKEDHAM June 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0335dd7e-1f5e-4068-b680-197de6c0af68`.
