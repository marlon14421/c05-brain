---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0361"
target_object: "T1218.009"
stix_relationship_id: "relationship--23d3f30e-9f30-4411-abba-04d31573205a"
---
# Relationship 1504: DET0361 — detects → T1218.009

**Source object:** [[01 ATT&CK/DET0361 - Detecting .NET COM Registration Abuse via Regsvcs-Regasm|DET0361: Detecting .NET COM Registration Abuse via Regsvcs/Regasm]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1218.009 - Regsvcs-Regasm|T1218.009: Regsvcs/Regasm]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--23d3f30e-9f30-4411-abba-04d31573205a`.
