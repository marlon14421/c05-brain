---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0378"
target_object: "T1090"
stix_relationship_id: "relationship--82758a74-b7e2-4839-ad52-bdc6c57c0dba"
---
# Relationship 4059: S0378 — uses → T1090

**Source object:** [[01 ATT&CK/S0378 - PoshC2|S0378: PoshC2]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090 - Proxy|T1090: Proxy]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[PoshC2](https://attack.mitre.org/software/S0378) contains modules that allow for use of proxies in command and control.(Citation: GitHub PoshC2)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--82758a74-b7e2-4839-ad52-bdc6c57c0dba`.
