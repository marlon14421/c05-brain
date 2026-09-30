---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1045"
target_object: "T1040"
stix_relationship_id: "relationship--706be608-c046-402e-ad71-c6042e0f88f2"
---
# Relationship 2894: G1045 — uses → T1040

**Source object:** [[01 ATT&CK/G1045 - Salt Typhoon|G1045: Salt Typhoon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1040 - Network Sniffing|T1040: Network Sniffing]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Salt Typhoon](https://attack.mitre.org/groups/G1045) has used a variety of tools and techniques to capture packet data between network interfaces.(Citation: Cisco Salt Typhoon FEB 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--706be608-c046-402e-ad71-c6042e0f88f2`.
