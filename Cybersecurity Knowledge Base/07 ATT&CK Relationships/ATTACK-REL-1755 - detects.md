---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0512"
target_object: "T1048.002"
stix_relationship_id: "relationship--9cdfdc91-f659-40f9-af35-404ad07be215"
---
# Relationship 1755: DET0512 — detects → T1048.002

**Source object:** [[01 ATT&CK/DET0512 - Detection of Exfiltration Over Asymmetric Encrypted Non-C2 Protocol|DET0512: Detection of Exfiltration Over Asymmetric Encrypted Non-C2 Protocol]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1048.002 - Exfiltration Over Asymmetric Encrypted Non-C2 Protocol|T1048.002: Exfiltration Over Asymmetric Encrypted Non-C2 Protocol]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9cdfdc91-f659-40f9-af35-404ad07be215`.
