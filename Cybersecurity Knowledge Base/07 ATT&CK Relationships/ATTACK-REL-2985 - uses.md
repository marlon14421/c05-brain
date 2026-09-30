---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0021"
target_object: "T1566.001"
stix_relationship_id: "relationship--5a9f2571-e611-4f7f-b0c9-6fc2d306b2f6"
---
# Relationship 2985: G0021 — uses → T1566.001

**Source object:** [[01 ATT&CK/G0021 - Molerats|G0021: Molerats]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.001 - Spearphishing Attachment|T1566.001: Spearphishing Attachment]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Molerats](https://attack.mitre.org/groups/G0021) has sent phishing emails with malicious Microsoft Word and PDF attachments.(Citation: Kaspersky MoleRATs April 2019)(Citation: Unit42 Molerat Mar 2020)(Citation: Cybereason Molerats Dec 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5a9f2571-e611-4f7f-b0c9-6fc2d306b2f6`.
