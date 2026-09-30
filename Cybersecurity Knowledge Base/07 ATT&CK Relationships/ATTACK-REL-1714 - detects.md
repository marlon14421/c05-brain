---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0505"
target_object: "T1027.010"
stix_relationship_id: "relationship--29eaf11e-f8e1-4690-aaff-d147eb8333f7"
---
# Relationship 1714: DET0505 — detects → T1027.010

**Source object:** [[01 ATT&CK/DET0505 - Detection Strategy for Command Obfuscation|DET0505: Detection Strategy for Command Obfuscation]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1027.010 - Command Obfuscation|T1027.010: Command Obfuscation]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--29eaf11e-f8e1-4690-aaff-d147eb8333f7`.
