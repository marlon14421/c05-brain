---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1206"
target_object: "T1104"
stix_relationship_id: "relationship--6114128d-66e6-4b94-9593-220f9e326cef"
---
# Relationship 4244: S1206 — uses → T1104

**Source object:** [[01 ATT&CK/S1206 - JumbledPath|S1206: JumbledPath]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1104 - Multi-Stage Channels|T1104: Multi-Stage Channels]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[JumbledPath](https://attack.mitre.org/software/S1206) can communicate over a unique series of connections to send and retrieve data from exploited devices.(Citation: Cisco Salt Typhoon FEB 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6114128d-66e6-4b94-9593-220f9e326cef`.
