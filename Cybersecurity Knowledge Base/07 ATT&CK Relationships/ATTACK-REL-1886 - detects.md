---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0080"
target_object: "T1190"
stix_relationship_id: "relationship--69e8d620-b9a1-4bfd-9bf0-62d2915f08ad"
---
# Relationship 1886: DET0080 — detects → T1190

**Source object:** [[01 ATT&CK/DET0080 - Exploit Public-Facing Application – multi-signal correlation (request → error → post-|DET0080: Exploit Public-Facing Application – multi-signal correlation (request → error → post-exploit process/egress)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1190 - Exploit Public-Facing Application|T1190: Exploit Public-Facing Application]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--69e8d620-b9a1-4bfd-9bf0-62d2915f08ad`.
