---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1047"
target_object: "T1505.006"
stix_relationship_id: "relationship--f88e7fa8-59aa-42c2-bf67-1b754eb0fac9"
---
# Relationship 1355: M1047 — mitigates → T1505.006

**Source object:** [[01 ATT&CK/M1047 - Audit|M1047: Audit]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1505.006 - vSphere Installation Bundles|T1505.006: vSphere Installation Bundles]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Periodically audit ESXi hosts to ensure that only approved VIBs are installed. The command `esxcli software vib list` lists installed VIBs, while the command `esxcli software vib signature verify` verifies the signatures of installed VIBs.(Citation: Google Cloud Threat Intelligence ESXi VIBs 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f88e7fa8-59aa-42c2-bf67-1b754eb0fac9`.
