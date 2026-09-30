---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0099"
target_object: "T1204.002"
stix_relationship_id: "relationship--20599767-204a-4cbf-ada7-0f931ee925e4"
---
# Relationship 3716: G0099 — uses → T1204.002

**Source object:** [[01 ATT&CK/G0099 - APT-C-36|G0099: APT-C-36]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[APT-C-36](https://attack.mitre.org/groups/G0099) has prompted victims to open attachments and to accept macros in order to execute the subsequent payload.(Citation: QiAnXin APT-C-36 Feb2019)(Citation: Recorded Future TAG-144 AUG 2025) [APT-C-36](https://attack.mitre.org/groups/G0099) has also lured victims into opening malicious files hosted on Google Drive that triggered WebDAV requests to download malware.(Citation: Check Point Blind Eagle MAR 2025)(Citation: Zscaler BlindEagle DEC 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--20599767-204a-4cbf-ada7-0f931ee925e4`.
