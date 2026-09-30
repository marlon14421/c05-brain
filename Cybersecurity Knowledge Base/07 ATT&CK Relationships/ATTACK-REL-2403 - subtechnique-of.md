---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1547.007"
target_object: "T1547"
stix_relationship_id: "relationship--25003c87-d031-4f1b-8204-9223f7426d28"
---
# Relationship 2403: T1547.007 — subtechnique-of → T1547

**Source object:** [[01 ATT&CK/T1547.007 - Re-opened Applications|T1547.007: Re-opened Applications]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1547 - Boot or Logon Autostart Execution|T1547: Boot or Logon Autostart Execution]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--25003c87-d031-4f1b-8204-9223f7426d28`.
