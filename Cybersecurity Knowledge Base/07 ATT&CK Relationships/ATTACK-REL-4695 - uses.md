---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0692"
target_object: "T1559.001"
stix_relationship_id: "relationship--c8b5bdf8-3d26-4ed7-ad0d-54e6a35a5d59"
---
# Relationship 4695: S0692 — uses → T1559.001

**Source object:** [[01 ATT&CK/S0692 - SILENTTRINITY|S0692: SILENTTRINITY]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1559.001 - Component Object Model|T1559.001: Component Object Model]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SILENTTRINITY](https://attack.mitre.org/software/S0692) can insert malicious shellcode into Excel.exe using a `Microsoft.Office.Interop` object.(Citation: Github_SILENTTRINITY)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c8b5bdf8-3d26-4ed7-ad0d-54e6a35a5d59`.
