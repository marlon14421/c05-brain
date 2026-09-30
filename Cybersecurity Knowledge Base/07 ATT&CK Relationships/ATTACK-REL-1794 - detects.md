---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0506"
target_object: "T1218.005"
stix_relationship_id: "relationship--8f29d6eb-f347-4e12-a318-14ee84974f85"
---
# Relationship 1794: DET0506 — detects → T1218.005

**Source object:** [[01 ATT&CK/DET0506 - Detecting Mshta-based Proxy Execution via Suspicious HTA or Script Invocation|DET0506: Detecting Mshta-based Proxy Execution via Suspicious HTA or Script Invocation]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1218.005 - Mshta|T1218.005: Mshta]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8f29d6eb-f347-4e12-a318-14ee84974f85`.
