---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1567.004"
target_object: "T1567"
stix_relationship_id: "relationship--f1793a83-f51c-48d4-b11e-ee9c93a28e71"
---
# Relationship 2200: T1567.004 — subtechnique-of → T1567

**Source object:** [[01 ATT&CK/T1567.004 - Exfiltration Over Webhook|T1567.004: Exfiltration Over Webhook]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1567 - Exfiltration Over Web Service|T1567: Exfiltration Over Web Service]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f1793a83-f51c-48d4-b11e-ee9c93a28e71`.
