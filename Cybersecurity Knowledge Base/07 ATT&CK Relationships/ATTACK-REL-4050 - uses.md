---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1139"
target_object: "T1566"
stix_relationship_id: "relationship--1787ebc1-29a3-4d93-ba24-baf11a4a7d19"
---
# Relationship 4050: S1139 — uses → T1566

**Source object:** [[01 ATT&CK/S1139 - INC Ransomware|S1139: INC Ransomware]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566 - Phishing|T1566: Phishing]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[INC Ransomware](https://attack.mitre.org/software/S1139) campaigns have used spearphishing emails for initial access.(Citation: SentinelOne INC Ransomware)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1787ebc1-29a3-4d93-ba24-baf11a4a7d19`.
