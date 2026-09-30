---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0435"
target_object: "T1071.001"
stix_relationship_id: "relationship--213423ab-05cf-4354-9cea-d536686cf21d"
---
# Relationship 3826: S0435 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0435 - PLEAD|S0435: PLEAD]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[PLEAD](https://attack.mitre.org/software/S0435) has used HTTP for communications with command and control (C2) servers.(Citation: JPCert PLEAD Downloader June 2018)(Citation: TrendMicro BlackTech June 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--213423ab-05cf-4354-9cea-d536686cf21d`.
