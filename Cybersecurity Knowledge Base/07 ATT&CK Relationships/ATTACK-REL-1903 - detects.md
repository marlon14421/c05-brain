---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0558"
target_object: "T1059.012"
stix_relationship_id: "relationship--bc324ee7-e55e-4edd-9f35-fc1a406f9f68"
---
# Relationship 1903: DET0558 — detects → T1059.012

**Source object:** [[01 ATT&CK/DET0558 - Detection Strategy for ESXi Hypervisor CLI Abuse|DET0558: Detection Strategy for ESXi Hypervisor CLI Abuse]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1059.012 - Hypervisor CLI|T1059.012: Hypervisor CLI]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bc324ee7-e55e-4edd-9f35-fc1a406f9f68`.
