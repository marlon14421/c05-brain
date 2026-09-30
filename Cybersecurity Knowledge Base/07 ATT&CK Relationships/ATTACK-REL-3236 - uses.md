---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0021"
target_object: "T1566.002"
stix_relationship_id: "relationship--aafab4f1-96d9-4c9e-8f87-98a38db520fe"
---
# Relationship 3236: C0021 — uses → T1566.002

**Source object:** [[01 ATT&CK/C0021 - C0021|C0021: C0021]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.002 - Spearphishing Link|T1566.002: Spearphishing Link]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [C0021](https://attack.mitre.org/campaigns/C0021), the threat actors sent phishing emails with unique malicious links, likely for tracking victim clicks.(Citation: FireEye APT29 Nov 2018)(Citation: Microsoft Unidentified Dec 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--aafab4f1-96d9-4c9e-8f87-98a38db520fe`.
