---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0689"
target_object: "T1071.001"
stix_relationship_id: "relationship--62c20028-7476-4358-8384-93d40cb65222"
---
# Relationship 3749: S0689 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0689 - WhisperGate|S0689: WhisperGate]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[WhisperGate](https://attack.mitre.org/software/S0689) can make an HTTPS connection to download additional files.(Citation: Unit 42 WhisperGate January 2022)(Citation: Medium S2W WhisperGate January 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--62c20028-7476-4358-8384-93d40cb65222`.
