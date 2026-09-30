---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0125"
target_object: "T1046"
stix_relationship_id: "relationship--e6b68811-113e-4f86-8096-9f506e34dda1"
---
# Relationship 4713: S0125 — uses → T1046

**Source object:** [[01 ATT&CK/S0125 - Remsec|S0125: Remsec]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1046 - Network Service Discovery|T1046: Network Service Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Remsec](https://attack.mitre.org/software/S0125) has a plugin that can perform ARP scanning as well as port scanning.(Citation: Kaspersky ProjectSauron Technical Analysis)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e6b68811-113e-4f86-8096-9f506e34dda1`.
