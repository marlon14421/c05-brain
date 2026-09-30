---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1684.002"
target_object: "T1684"
stix_relationship_id: "relationship--577e6f9a-e9f6-4f40-a18f-6a70b7783f63"
---
# Relationship 2219: T1684.002 — subtechnique-of → T1684

**Source object:** [[01 ATT&CK/T1684.002 - Email Spoofing|T1684.002: Email Spoofing]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1684 - Social Engineering|T1684: Social Engineering]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--577e6f9a-e9f6-4f40-a18f-6a70b7783f63`.
