---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0125"
target_object: "T1119"
stix_relationship_id: "relationship--5e1a2fcd-bb4e-43b2-8f42-33fb5bf80b21"
---
# Relationship 3390: G0125 — uses → T1119

**Source object:** [[01 ATT&CK/G0125 - HAFNIUM|G0125: HAFNIUM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1119 - Automated Collection|T1119: Automated Collection]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[HAFNIUM](https://attack.mitre.org/groups/G0125) has used MSGraph to exfiltrate data from email, OneDrive, and SharePoint.(Citation: Microsoft Silk Typhoon MAR 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5e1a2fcd-bb4e-43b2-8f42-33fb5bf80b21`.
