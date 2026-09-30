---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0047"
target_object: "T1114.001"
stix_relationship_id: "relationship--8397947f-ea47-40e3-8a0d-8e20365d022f"
---
# Relationship 1506: DET0047 — detects → T1114.001

**Source object:** [[01 ATT&CK/DET0047 - Detect Local Email Collection via Outlook Data File Access and Command Line Tooling|DET0047: Detect Local Email Collection via Outlook Data File Access and Command Line Tooling]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1114.001 - Local Email Collection|T1114.001: Local Email Collection]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8397947f-ea47-40e3-8a0d-8e20365d022f`.
