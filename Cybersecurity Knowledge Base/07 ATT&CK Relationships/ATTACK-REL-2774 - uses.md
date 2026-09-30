---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0128"
target_object: "T1566.002"
stix_relationship_id: "relationship--671a20b9-ad4c-468f-9871-be3545907dd2"
---
# Relationship 2774: G0128 — uses → T1566.002

**Source object:** [[01 ATT&CK/G0128 - ZIRCONIUM|G0128: ZIRCONIUM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.002 - Spearphishing Link|T1566.002: Spearphishing Link]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ZIRCONIUM](https://attack.mitre.org/groups/G0128) has used malicious links in e-mails to deliver malware.(Citation: Microsoft Targeting Elections September 2020)(Citation: Google Election Threats October 2020)(Citation: Zscaler APT31 Covid-19 October 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--671a20b9-ad4c-468f-9871-be3545907dd2`.
