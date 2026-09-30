---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0435"
target_object: "T1090"
stix_relationship_id: "relationship--6e23cb4f-61dd-4a6a-8c25-7eb79c376558"
---
# Relationship 3838: S0435 — uses → T1090

**Source object:** [[01 ATT&CK/S0435 - PLEAD|S0435: PLEAD]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090 - Proxy|T1090: Proxy]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[PLEAD](https://attack.mitre.org/software/S0435) has the ability to proxy network communications.(Citation: JPCert PLEAD Downloader June 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6e23cb4f-61dd-4a6a-8c25-7eb79c376558`.
