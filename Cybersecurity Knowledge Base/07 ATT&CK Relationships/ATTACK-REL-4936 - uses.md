---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0356"
target_object: "T1547.009"
stix_relationship_id: "relationship--e57361ca-1d03-4171-86e2-09f8c32cb319"
---
# Relationship 4936: S0356 — uses → T1547.009

**Source object:** [[01 ATT&CK/S0356 - KONNI|S0356: KONNI]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.009 - Shortcut Modification|T1547.009: Shortcut Modification]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

A version of [KONNI](https://attack.mitre.org/software/S0356) drops a Windows shortcut on the victim’s machine to establish persistence.(Citation: Talos Konni May 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e57361ca-1d03-4171-86e2-09f8c32cb319`.
