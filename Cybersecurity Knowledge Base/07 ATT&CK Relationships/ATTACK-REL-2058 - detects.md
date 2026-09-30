---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0145"
target_object: "T1686"
stix_relationship_id: "relationship--c927755f-1c4c-4cf2-a6bb-b043ef0ef2f4"
---
# Relationship 2058: DET0145 — detects → T1686

**Source object:** [[01 ATT&CK/DET0145 - Detection of Disabled or Modified System Firewalls across OS Platforms|DET0145: Detection of Disabled or Modified System Firewalls across OS Platforms.]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1686 - Disable or Modify System Firewall|T1686: Disable or Modify System Firewall]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c927755f-1c4c-4cf2-a6bb-b043ef0ef2f4`.
