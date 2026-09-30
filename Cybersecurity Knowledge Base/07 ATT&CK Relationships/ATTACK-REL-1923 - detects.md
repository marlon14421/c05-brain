---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0311"
target_object: "T1685.003"
stix_relationship_id: "relationship--58dc2b98-c557-4a65-9f7f-624c9f838288"
---
# Relationship 1923: DET0311 — detects → T1685.003

**Source object:** [[01 ATT&CK/DET0311 - Detection for Spoofing Tool UI across OS Platforms|DET0311: Detection for Spoofing Tool UI across OS Platforms]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1685.003 - Modify or Spoof Tool UI|T1685.003: Modify or Spoof Tool UI]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--58dc2b98-c557-4a65-9f7f-624c9f838288`.
