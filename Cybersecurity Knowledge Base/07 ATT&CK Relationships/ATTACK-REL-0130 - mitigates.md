---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1040"
target_object: "T1559"
stix_relationship_id: "relationship--ca928ba4-bb4b-4cd9-a105-8c0d4d81891f"
---
# Relationship 0130: M1040 — mitigates → T1559

**Source object:** [[01 ATT&CK/M1040 - Behavior Prevention on Endpoint|M1040: Behavior Prevention on Endpoint]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1559 - Inter-Process Communication|T1559: Inter-Process Communication]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

On Windows 10, enable Attack Surface Reduction (ASR) rules to prevent DDE attacks and spawning of child processes from Office programs.(Citation: Microsoft ASR Nov 2017)(Citation: Enigma Reviving DDE Jan 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ca928ba4-bb4b-4cd9-a105-8c0d4d81891f`.
