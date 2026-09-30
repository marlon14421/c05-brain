---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0147"
target_object: "T1496.004"
stix_relationship_id: "relationship--c353975a-cce4-4166-b632-f74f7e57c956"
---
# Relationship 1522: DET0147 — detects → T1496.004

**Source object:** [[01 ATT&CK/DET0147 - Detection Strategy for Cloud Service Hijacking via SaaS Abuse|DET0147: Detection Strategy for Cloud Service Hijacking via SaaS Abuse]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1496.004 - Cloud Service Hijacking|T1496.004: Cloud Service Hijacking]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c353975a-cce4-4166-b632-f74f7e57c956`.
