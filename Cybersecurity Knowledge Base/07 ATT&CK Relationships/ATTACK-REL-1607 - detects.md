---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0567"
target_object: "T1213.005"
stix_relationship_id: "relationship--9ea8e5a8-93ad-48c6-b896-6b32025299a4"
---
# Relationship 1607: DET0567 — detects → T1213.005

**Source object:** [[01 ATT&CK/DET0567 - Detecting Unauthorized Collection from Messaging Applications in SaaS and Office Envi|DET0567: Detecting Unauthorized Collection from Messaging Applications in SaaS and Office Environments]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1213.005 - Messaging Applications|T1213.005: Messaging Applications]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9ea8e5a8-93ad-48c6-b896-6b32025299a4`.
