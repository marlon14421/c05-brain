---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0382"
target_object: "T1136.001"
stix_relationship_id: "relationship--5db107fe-7b8d-4093-a551-492eb4a72ed9"
---
# Relationship 3768: S0382 — uses → T1136.001

**Source object:** [[01 ATT&CK/S0382 - ServHelper|S0382: ServHelper]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1136.001 - Local Account|T1136.001: Local Account]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ServHelper](https://attack.mitre.org/software/S0382) has created a new user named "supportaccount".(Citation: Proofpoint TA505 Jan 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5db107fe-7b8d-4093-a551-492eb4a72ed9`.
