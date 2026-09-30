---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1134.002"
target_object: "T1134"
stix_relationship_id: "relationship--9f163bcc-193b-49f4-884d-4246dff23e6c"
---
# Relationship 2458: T1134.002 — subtechnique-of → T1134

**Source object:** [[01 ATT&CK/T1134.002 - Create Process with Token|T1134.002: Create Process with Token]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1134 - Access Token Manipulation|T1134: Access Token Manipulation]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9f163bcc-193b-49f4-884d-4246dff23e6c`.
