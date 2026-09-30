---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0115"
target_object: "T1199"
stix_relationship_id: "relationship--1567be6a-0231-4605-b92b-ae1bc5e1bb4e"
---
# Relationship 3160: G0115 — uses → T1199

**Source object:** [[01 ATT&CK/G0115 - GOLD SOUTHFIELD|G0115: GOLD SOUTHFIELD]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1199 - Trusted Relationship|T1199: Trusted Relationship]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[GOLD SOUTHFIELD](https://attack.mitre.org/groups/G0115) has breached Managed Service Providers (MSP's) to deliver malware to MSP customers.(Citation: Secureworks REvil September 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1567be6a-0231-4605-b92b-ae1bc5e1bb4e`.
