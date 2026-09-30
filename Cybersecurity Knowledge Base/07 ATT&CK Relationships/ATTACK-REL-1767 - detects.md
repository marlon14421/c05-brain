---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0389"
target_object: "T1055.001"
stix_relationship_id: "relationship--3746842c-52cb-4b8a-88d3-387da906410e"
---
# Relationship 1767: DET0389 — detects → T1055.001

**Source object:** [[01 ATT&CK/DET0389 - Behavioral Detection of DLL Injection via Windows API|DET0389: Behavioral Detection of DLL Injection via Windows API]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1055.001 - Dynamic-link Library Injection|T1055.001: Dynamic-link Library Injection]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3746842c-52cb-4b8a-88d3-387da906410e`.
