---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0103"
target_object: "T1204.002"
stix_relationship_id: "relationship--b91c4f2d-8f21-46e9-a012-967436018eea"
---
# Relationship 4313: G0103 — uses → T1204.002

**Source object:** [[01 ATT&CK/G0103 - Mofang|G0103: Mofang]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Mofang](https://attack.mitre.org/groups/G0103)'s malicious spearphishing attachments required a user to open the file after receiving.(Citation: FOX-IT May 2016 Mofang)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b91c4f2d-8f21-46e9-a012-967436018eea`.
