---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0331"
target_object: "T1555"
stix_relationship_id: "relationship--ae151f0a-374b-47c0-a4e6-b9bdc7ee55b5"
---
# Relationship 4395: S0331 — uses → T1555

**Source object:** [[01 ATT&CK/S0331 - Agent Tesla|S0331: Agent Tesla]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1555 - Credentials from Password Stores|T1555: Credentials from Password Stores]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Agent Tesla](https://attack.mitre.org/software/S0331) has the ability to steal credentials from FTP clients and wireless profiles.(Citation: Malwarebytes Agent Tesla April 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ae151f0a-374b-47c0-a4e6-b9bdc7ee55b5`.
