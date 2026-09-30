---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1213"
target_object: "T1071.001"
stix_relationship_id: "relationship--e571239e-b3d9-49b1-a418-77455d7a5312"
---
# Relationship 2973: S1213 — uses → T1071.001

**Source object:** [[01 ATT&CK/S1213 - Lumma Stealer|S1213: Lumma Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Lumma Stealer](https://attack.mitre.org/software/S1213) has used HTTP and HTTP for command and control communication.(Citation: Qualys LummaStealer 2024)(Citation: Fortinet LummaStealer 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e571239e-b3d9-49b1-a418-77455d7a5312`.
