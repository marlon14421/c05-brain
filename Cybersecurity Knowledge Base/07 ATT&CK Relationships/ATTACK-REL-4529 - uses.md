---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0092"
target_object: "T1087.003"
stix_relationship_id: "relationship--02c88228-8275-42a7-9c3a-d5393556bceb"
---
# Relationship 4529: G0092 — uses → T1087.003

**Source object:** [[01 ATT&CK/G0092 - TA505|G0092: TA505]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1087.003 - Email Account|T1087.003: Email Account]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[TA505](https://attack.mitre.org/groups/G0092) has used the tool EmailStealer to steal and send lists of e-mail addresses to a remote server.(Citation: Trend Micro TA505 June 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--02c88228-8275-42a7-9c3a-d5393556bceb`.
