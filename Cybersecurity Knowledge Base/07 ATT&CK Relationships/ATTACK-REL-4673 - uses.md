---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0011"
target_object: "T1608.001"
stix_relationship_id: "relationship--1a28bcb2-fbac-4bc3-a42c-a254b3e9643e"
---
# Relationship 4673: C0011 — uses → T1608.001

**Source object:** [[01 ATT&CK/C0011 - C0011|C0011: C0011]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1608.001 - Upload Malware|T1608.001: Upload Malware]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

For [C0011](https://attack.mitre.org/campaigns/C0011), [Transparent Tribe](https://attack.mitre.org/groups/G0134) hosted malicious documents on domains registered by the group.(Citation: Cisco Talos Transparent Tribe Education Campaign July 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1a28bcb2-fbac-4bc3-a42c-a254b3e9643e`.
