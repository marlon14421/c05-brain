---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0560"
target_object: "T1112"
stix_relationship_id: "relationship--69356661-76fb-46fe-94ce-d029ee7f8a64"
---
# Relationship 2755: S0560 — uses → T1112

**Source object:** [[01 ATT&CK/S0560 - TEARDROP|S0560: TEARDROP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1112 - Modify Registry|T1112: Modify Registry]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[TEARDROP](https://attack.mitre.org/software/S0560) modified the Registry to create a Windows service for itself on a compromised host.(Citation: Check Point Sunburst Teardrop December 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--69356661-76fb-46fe-94ce-d029ee7f8a64`.
