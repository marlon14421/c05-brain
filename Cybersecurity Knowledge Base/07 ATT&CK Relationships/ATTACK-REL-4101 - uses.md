---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0081"
target_object: "T1055.001"
stix_relationship_id: "relationship--f72d9605-eea6-4ed4-8502-231d4c21431f"
---
# Relationship 4101: S0081 — uses → T1055.001

**Source object:** [[01 ATT&CK/S0081 - Elise|S0081: Elise]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.001 - Dynamic-link Library Injection|T1055.001: Dynamic-link Library Injection]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Elise](https://attack.mitre.org/software/S0081) injects DLL files into iexplore.exe.(Citation: Lotus Blossom Jun 2015)(Citation: Accenture Dragonfish Jan 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f72d9605-eea6-4ed4-8502-231d4c21431f`.
