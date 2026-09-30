---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1210"
target_object: "T1055.001"
stix_relationship_id: "relationship--5451c465-0b5d-451c-bdaa-55165e408b9b"
---
# Relationship 3283: S1210 — uses → T1055.001

**Source object:** [[01 ATT&CK/S1210 - Sagerunex|S1210: Sagerunex]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.001 - Dynamic-link Library Injection|T1055.001: Dynamic-link Library Injection]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Sagerunex](https://attack.mitre.org/software/S1210) is designed to be dynamic link library (DLL) injected into an infected endpoint and executed directly in memory.(Citation: Cisco LotusBlossom 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5451c465-0b5d-451c-bdaa-55165e408b9b`.
