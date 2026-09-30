---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0246"
target_object: "T1111"
stix_relationship_id: "relationship--16857a1a-a782-4c5e-952d-bf00b8f0d782"
---
# Relationship 1689: DET0246 — detects → T1111

**Source object:** [[01 ATT&CK/DET0246 - Detection Strategy for MFA Interception via Input Capture and Smart Card Proxying|DET0246: Detection Strategy for MFA Interception via Input Capture and Smart Card Proxying]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1111 - Multi-Factor Authentication Interception|T1111: Multi-Factor Authentication Interception]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--16857a1a-a782-4c5e-952d-bf00b8f0d782`.
