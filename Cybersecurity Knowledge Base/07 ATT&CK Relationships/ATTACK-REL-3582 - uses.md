---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0276"
target_object: "T1036.006"
stix_relationship_id: "relationship--b9688abd-0f6d-4c76-8b73-d9fe7d11f07f"
---
# Relationship 3582: S0276 — uses → T1036.006

**Source object:** [[01 ATT&CK/S0276 - Keydnap|S0276: Keydnap]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.006 - Space after Filename|T1036.006: Space after Filename]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Keydnap](https://attack.mitre.org/software/S0276) puts a space after a false .jpg extension so that execution actually goes through the Terminal.app program.(Citation: synack 2016 review)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b9688abd-0f6d-4c76-8b73-d9fe7d11f07f`.
