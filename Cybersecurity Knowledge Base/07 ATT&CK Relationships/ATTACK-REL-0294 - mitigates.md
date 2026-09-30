---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1045"
target_object: "T1505.006"
stix_relationship_id: "relationship--e4032a95-3f15-4c00-9014-2648c79c2fac"
---
# Relationship 0294: M1045 — mitigates → T1505.006

**Source object:** [[01 ATT&CK/M1045 - Code Signing|M1045: Code Signing]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1505.006 - vSphere Installation Bundles|T1505.006: vSphere Installation Bundles]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Enabling the `execInstalledOnly` feature prevents unsigned binaries from being run on ESXi hosts.(Citation: Google Cloud Threat Intelligence ESXi Hardening 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e4032a95-3f15-4c00-9014-2648c79c2fac`.
