---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1098.005"
target_object: "T1098"
stix_relationship_id: "relationship--81a6a1c2-a834-47ed-ba5e-3048c62115ff"
---
# Relationship 2453: T1098.005 — subtechnique-of → T1098

**Source object:** [[01 ATT&CK/T1098.005 - Device Registration|T1098.005: Device Registration]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1098 - Account Manipulation|T1098: Account Manipulation]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--81a6a1c2-a834-47ed-ba5e-3048c62115ff`.
