---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1027.007"
target_object: "T1027"
stix_relationship_id: "relationship--7c30237d-5d03-4f5f-9488-3629f2b1813c"
---
# Relationship 2207: T1027.007 — subtechnique-of → T1027

**Source object:** [[01 ATT&CK/T1027.007 - Dynamic API Resolution|T1027.007: Dynamic API Resolution]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7c30237d-5d03-4f5f-9488-3629f2b1813c`.
