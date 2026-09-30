---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1122"
target_object: "T1204.002"
stix_relationship_id: "relationship--4f5d4ab0-6514-4a99-a5b9-456c903e4717"
---
# Relationship 3157: S1122 — uses → T1204.002

**Source object:** [[01 ATT&CK/S1122 - Mispadu|S1122: Mispadu]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Mispadu](https://attack.mitre.org/software/S1122) has relied on users to execute malicious files in order to gain execution on victim machines.(Citation: ESET Security Mispadu Facebook Ads 2019)(Citation: Metabase Q Mispadu Trojan 2023)(Citation: SCILabs Malteiro 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4f5d4ab0-6514-4a99-a5b9-456c903e4717`.
