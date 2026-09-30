---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0690"
target_object: "T1005"
stix_relationship_id: "relationship--9fd8bbd8-1d8d-426d-b079-c7cc2ebd4b35"
---
# Relationship 3223: S0690 — uses → T1005

**Source object:** [[01 ATT&CK/S0690 - Green Lambert|S0690: Green Lambert]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Green Lambert](https://attack.mitre.org/software/S0690) can collect data from a compromised host.(Citation: Objective See Green Lambert for OSX Oct 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9fd8bbd8-1d8d-426d-b079-c7cc2ebd4b35`.
