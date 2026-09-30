---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0138"
target_object: "T1218.004"
stix_relationship_id: "relationship--a78534d4-b98e-4acd-8e51-337d5bb7877c"
---
# Relationship 1910: DET0138 — detects → T1218.004

**Source object:** [[01 ATT&CK/DET0138 - Detection of Malicious Code Execution via InstallUtil.exe|DET0138: Detection of Malicious Code Execution via InstallUtil.exe]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1218.004 - InstallUtil|T1218.004: InstallUtil]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a78534d4-b98e-4acd-8e51-337d5bb7877c`.
