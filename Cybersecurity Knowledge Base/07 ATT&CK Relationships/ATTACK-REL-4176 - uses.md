---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0060"
target_object: "T1560.001"
stix_relationship_id: "relationship--99e9583f-433d-437d-bf37-7ea2b3f1b613"
---
# Relationship 4176: G0060 — uses → T1560.001

**Source object:** [[01 ATT&CK/G0060 - BRONZE BUTLER|G0060: BRONZE BUTLER]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1560.001 - Archive via Utility|T1560.001: Archive via Utility]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BRONZE BUTLER](https://attack.mitre.org/groups/G0060) has compressed data into password-protected RAR archives prior to exfiltration.(Citation: Secureworks BRONZE BUTLER Oct 2017)(Citation: Trend Micro Tick November 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--99e9583f-433d-437d-bf37-7ea2b3f1b613`.
