---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0090"
target_object: "T1583.001"
stix_relationship_id: "relationship--7dafbab4-84ba-4fbf-a055-f4323305c4b9"
---
# Relationship 2947: G0090 — uses → T1583.001

**Source object:** [[01 ATT&CK/G0090 - WIRTE|G0090: WIRTE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1583.001 - Domains|T1583.001: Domains]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[WIRTE](https://attack.mitre.org/groups/G0090) has registered domains designed to mimic legitimate sites for use in phishing campaigns.(Citation: Check Point Wirte NOV 2024)(Citation: Palo Alto Ashen Lepus DEC 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7dafbab4-84ba-4fbf-a055-f4323305c4b9`.
