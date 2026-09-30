---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0199"
target_object: "T1105"
stix_relationship_id: "relationship--1251d1e2-21d3-48f2-a869-44507b34943a"
---
# Relationship 3413: S0199 — uses → T1105

**Source object:** [[01 ATT&CK/S0199 - TURNEDUP|S0199: TURNEDUP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[TURNEDUP](https://attack.mitre.org/software/S0199) is capable of downloading additional files.(Citation: FireEye APT33 Sept 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1251d1e2-21d3-48f2-a869-44507b34943a`.
