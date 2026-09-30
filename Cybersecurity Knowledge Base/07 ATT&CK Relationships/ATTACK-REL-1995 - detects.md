---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0327"
target_object: "T1021.001"
stix_relationship_id: "relationship--ef887220-356b-4756-8c65-586441765961"
---
# Relationship 1995: DET0327 — detects → T1021.001

**Source object:** [[01 ATT&CK/DET0327 - Multi-event Detection Strategy for RDP-Based Remote Logins and Post-Access Activity|DET0327: Multi-event Detection Strategy for RDP-Based Remote Logins and Post-Access Activity]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1021.001 - Remote Desktop Protocol|T1021.001: Remote Desktop Protocol]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ef887220-356b-4756-8c65-586441765961`.
