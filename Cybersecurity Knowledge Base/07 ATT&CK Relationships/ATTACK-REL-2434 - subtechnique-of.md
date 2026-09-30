---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1606.001"
target_object: "T1606"
stix_relationship_id: "relationship--7cf1506f-3064-4d8f-ac50-ff6b9a4fd3c3"
---
# Relationship 2434: T1606.001 — subtechnique-of → T1606

**Source object:** [[01 ATT&CK/T1606.001 - Web Cookies|T1606.001: Web Cookies]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1606 - Forge Web Credentials|T1606: Forge Web Credentials]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7cf1506f-3064-4d8f-ac50-ff6b9a4fd3c3`.
