---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0632"
target_object: "T1132.001"
stix_relationship_id: "relationship--50f0d6ac-0cfa-41d6-9795-e6843101c524"
---
# Relationship 4082: S0632 — uses → T1132.001

**Source object:** [[01 ATT&CK/S0632 - GrimAgent|S0632: GrimAgent]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1132.001 - Standard Encoding|T1132.001: Standard Encoding]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[GrimAgent](https://attack.mitre.org/software/S0632) can base64 encode C2 replies.(Citation: Group IB GrimAgent July 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--50f0d6ac-0cfa-41d6-9795-e6843101c524`.
