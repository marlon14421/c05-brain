---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1685.006"
target_object: "T1685"
stix_relationship_id: "relationship--72ffe99f-3b8e-4681-a553-f9fccd47404d"
---
# Relationship 2250: T1685.006 — subtechnique-of → T1685

**Source object:** [[01 ATT&CK/T1685.006 - Clear Linux or Mac System Logs|T1685.006: Clear Linux or Mac System Logs]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1685 - Disable or Modify Tools|T1685: Disable or Modify Tools]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--72ffe99f-3b8e-4681-a553-f9fccd47404d`.
