---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1206"
target_object: "T1040"
stix_relationship_id: "relationship--335ed0b0-c96a-4868-9443-d45d05c16ba8"
---
# Relationship 4365: S1206 — uses → T1040

**Source object:** [[01 ATT&CK/S1206 - JumbledPath|S1206: JumbledPath]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1040 - Network Sniffing|T1040: Network Sniffing]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[JumbledPath](https://attack.mitre.org/software/S1206) has the ability to perform packet capture on remote devices via actor-defined jump-hosts.(Citation: Cisco Salt Typhoon FEB 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--335ed0b0-c96a-4868-9443-d45d05c16ba8`.
