---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0501"
target_object: "T1027.011"
stix_relationship_id: "relationship--e27416ae-e9f1-4b3f-90b2-6cb4a1a6abf4"
---
# Relationship 3726: S0501 — uses → T1027.011

**Source object:** [[01 ATT&CK/S0501 - PipeMon|S0501: PipeMon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.011 - Fileless Storage|T1027.011: Fileless Storage]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[PipeMon](https://attack.mitre.org/software/S0501) has stored its encrypted payload in the Registry under `HKLM\SOFTWARE\Microsoft\Print\Components\`.(Citation: ESET PipeMon May 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e27416ae-e9f1-4b3f-90b2-6cb4a1a6abf4`.
