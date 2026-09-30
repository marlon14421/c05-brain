---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0143"
target_object: "T1573.001"
stix_relationship_id: "relationship--5beb9a05-f114-4a99-802f-c171529ceab1"
---
# Relationship 1710: DET0143 — detects → T1573.001

**Source object:** [[01 ATT&CK/DET0143 - Detection Strategy for Encrypted Channel via Symmetric Cryptography across OS Platfor|DET0143: Detection Strategy for Encrypted Channel via Symmetric Cryptography across OS Platforms]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5beb9a05-f114-4a99-802f-c171529ceab1`.
