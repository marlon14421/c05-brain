---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0011"
target_object: "T1055.001"
stix_relationship_id: "relationship--5e840479-61c1-44f5-8cb8-0e61ffe12b89"
---
# Relationship 3213: S0011 — uses → T1055.001

**Source object:** [[01 ATT&CK/S0011 - Taidoor|S0011: Taidoor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.001 - Dynamic-link Library Injection|T1055.001: Dynamic-link Library Injection]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Taidoor](https://attack.mitre.org/software/S0011) can perform DLL loading.(Citation: TrendMicro Taidoor)(Citation: CISA MAR-10292089-1.v2 TAIDOOR August 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5e840479-61c1-44f5-8cb8-0e61ffe12b89`.
