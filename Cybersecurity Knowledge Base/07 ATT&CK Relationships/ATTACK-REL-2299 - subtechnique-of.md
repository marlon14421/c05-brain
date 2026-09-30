---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1016.002"
target_object: "T1016"
stix_relationship_id: "relationship--6e5f5721-411f-4012-8f52-26e24f6782ea"
---
# Relationship 2299: T1016.002 — subtechnique-of → T1016

**Source object:** [[01 ATT&CK/T1016.002 - Wi-Fi Discovery|T1016.002: Wi-Fi Discovery]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6e5f5721-411f-4012-8f52-26e24f6782ea`.
