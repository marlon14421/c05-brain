---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9020"
target_object: "T1204.002"
stix_relationship_id: "relationship--95615d72-da27-42f5-b7a3-a2651ca68a2a"
---
# Relationship 4656: S9020 — uses → T1204.002

**Source object:** [[01 ATT&CK/S9020 - LODEINFO|S9020: LODEINFO]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[LODEINFO](https://attack.mitre.org/software/S9020) has been executed via victims opening malicious email attachments.(Citation: Kaspersky LODEINFO OCT 2022)(Citation: ESET MirrorFace DEC 2022)(Citation: ITOCHU LODEINFO JAN 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--95615d72-da27-42f5-b7a3-a2651ca68a2a`.
