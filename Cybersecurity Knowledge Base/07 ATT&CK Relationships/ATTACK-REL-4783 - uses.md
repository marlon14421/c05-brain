---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0517"
target_object: "T1070.004"
stix_relationship_id: "relationship--d0c8b03f-7c57-4156-bc5e-cd0c45327ef3"
---
# Relationship 4783: S0517 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0517 - Pillowmint|S0517: Pillowmint]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Pillowmint](https://attack.mitre.org/software/S0517) has deleted the filepath %APPDATA%\Intel\devmonsrv.exe .(Citation: Trustwave Pillowmint June 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d0c8b03f-7c57-4156-bc5e-cd0c45327ef3`.
