---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0457"
target_object: "T1055.001"
stix_relationship_id: "relationship--f1091b2c-ea09-402b-9717-8b7526fb5c13"
---
# Relationship 3489: S0457 — uses → T1055.001

**Source object:** [[01 ATT&CK/S0457 - Netwalker|S0457: Netwalker]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.001 - Dynamic-link Library Injection|T1055.001: Dynamic-link Library Injection]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

The [Netwalker](https://attack.mitre.org/software/S0457) DLL has been injected reflectively into the memory of a legitimate running process.(Citation: TrendMicro Netwalker May 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f1091b2c-ea09-402b-9717-8b7526fb5c13`.
