---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0185"
target_object: "T1550.001"
stix_relationship_id: "relationship--0e9e47fe-32f5-4f5f-ba27-fae27c9f7664"
---
# Relationship 1897: DET0185 — detects → T1550.001

**Source object:** [[01 ATT&CK/DET0185 - Behavioral Detection Strategy for Use Alternate Authentication Material- Application |DET0185: Behavioral Detection Strategy for Use Alternate Authentication Material: Application Access Token (T1550.001)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1550.001 - Application Access Token|T1550.001: Application Access Token]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0e9e47fe-32f5-4f5f-ba27-fae27c9f7664`.
