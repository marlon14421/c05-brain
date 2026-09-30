---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0664"
target_object: "T1543.003"
stix_relationship_id: "relationship--60331850-dfc3-4769-9790-1be664aa63c2"
---
# Relationship 3328: S0664 — uses → T1543.003

**Source object:** [[01 ATT&CK/S0664 - Pandora|S0664: Pandora]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1543.003 - Windows Service|T1543.003: Windows Service]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Pandora](https://attack.mitre.org/software/S0664) has the ability to gain system privileges through Windows services.(Citation: Trend Micro Iron Tiger April 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--60331850-dfc3-4769-9790-1be664aa63c2`.
