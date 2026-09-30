---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1059"
target_object: "T1620"
stix_relationship_id: "relationship--507d0a52-450a-4bb9-8667-e787f8c589f2"
---
# Relationship 2819: S1059 — uses → T1620

**Source object:** [[01 ATT&CK/S1059 - metaMain|S1059: metaMain]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1620 - Reflective Code Loading|T1620: Reflective Code Loading]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[metaMain](https://attack.mitre.org/software/S1059) has reflectively loaded a DLL to read, decrypt, and load an orchestrator file.(Citation: SentinelLabs Metador Sept 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--507d0a52-450a-4bb9-8667-e787f8c589f2`.
