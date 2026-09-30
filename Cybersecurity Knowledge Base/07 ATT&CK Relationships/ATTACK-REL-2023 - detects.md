---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0054"
target_object: "T1534"
stix_relationship_id: "relationship--6e565457-f873-40b8-aa6a-b1b59f31a47a"
---
# Relationship 2023: DET0054 — detects → T1534

**Source object:** [[01 ATT&CK/DET0054 - Internal Spearphishing via Trusted Accounts|DET0054: Internal Spearphishing via Trusted Accounts]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1534 - Internal Spearphishing|T1534: Internal Spearphishing]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6e565457-f873-40b8-aa6a-b1b59f31a47a`.
