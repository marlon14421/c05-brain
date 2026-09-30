---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1048.002"
target_object: "T1048"
stix_relationship_id: "relationship--6b9361fc-6a9e-4fc3-bc53-72a3f616869a"
---
# Relationship 2202: T1048.002 — subtechnique-of → T1048

**Source object:** [[01 ATT&CK/T1048.002 - Exfiltration Over Asymmetric Encrypted Non-C2 Protocol|T1048.002: Exfiltration Over Asymmetric Encrypted Non-C2 Protocol]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1048 - Exfiltration Over Alternative Protocol|T1048: Exfiltration Over Alternative Protocol]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6b9361fc-6a9e-4fc3-bc53-72a3f616869a`.
