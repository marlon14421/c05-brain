---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0059"
target_object: "T1102.002"
stix_relationship_id: "relationship--79f89b33-046c-4bfa-a12d-c50fa0d84ea6"
---
# Relationship 3380: G0059 — uses → T1102.002

**Source object:** [[01 ATT&CK/G0059 - Magic Hound|G0059: Magic Hound]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1102.002 - Bidirectional Communication|T1102.002: Bidirectional Communication]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Magic Hound](https://attack.mitre.org/groups/G0059) malware can use a SOAP Web service to communicate with its C2 server.(Citation: Unit 42 Magic Hound Feb 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--79f89b33-046c-4bfa-a12d-c50fa0d84ea6`.
