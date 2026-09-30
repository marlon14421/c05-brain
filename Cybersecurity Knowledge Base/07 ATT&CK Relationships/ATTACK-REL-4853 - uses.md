---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0438"
target_object: "T1129"
stix_relationship_id: "relationship--831513ed-bbf2-406f-ab74-bfffa8a376b7"
---
# Relationship 4853: S0438 — uses → T1129

**Source object:** [[01 ATT&CK/S0438 - Attor|S0438: Attor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1129 - Shared Modules|T1129: Shared Modules]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Attor](https://attack.mitre.org/software/S0438)'s dispatcher can execute additional plugins by loading the respective DLLs.(Citation: ESET Attor Oct 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--831513ed-bbf2-406f-ab74-bfffa8a376b7`.
