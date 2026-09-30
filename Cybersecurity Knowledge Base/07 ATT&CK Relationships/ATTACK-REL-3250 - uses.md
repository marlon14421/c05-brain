---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0027"
target_object: "T1098.003"
stix_relationship_id: "relationship--4e23f18f-9418-462d-9f59-a527cb15ba9d"
---
# Relationship 3250: C0027 — uses → T1098.003

**Source object:** [[01 ATT&CK/C0027 - C0027|C0027: C0027]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1098.003 - Additional Cloud Roles|T1098.003: Additional Cloud Roles]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [C0027](https://attack.mitre.org/campaigns/C0027), [Scattered Spider](https://attack.mitre.org/groups/G1015) used IAM manipulation to gain persistence and to assume or elevate privileges.(Citation: Crowdstrike TELCO BPO Campaign December 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4e23f18f-9418-462d-9f59-a527cb15ba9d`.
