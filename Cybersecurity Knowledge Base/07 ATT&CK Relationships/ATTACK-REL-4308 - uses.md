---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1040"
target_object: "T1560.001"
stix_relationship_id: "relationship--48ff3270-ada9-4f02-b4f4-bfd6a3a3865f"
---
# Relationship 4308: G1040 — uses → T1560.001

**Source object:** [[01 ATT&CK/G1040 - Play|G1040: Play]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1560.001 - Archive via Utility|T1560.001: Archive via Utility]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Play](https://attack.mitre.org/groups/G1040) has used WinRAR to compress files prior to exfiltration.(Citation: CISA Play Ransomware Advisory December 2023)(Citation: Trend Micro Ransomware Spotlight Play July 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--48ff3270-ada9-4f02-b4f4-bfd6a3a3865f`.
