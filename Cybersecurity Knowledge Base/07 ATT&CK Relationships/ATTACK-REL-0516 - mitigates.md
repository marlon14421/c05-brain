---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1041"
target_object: "T1003"
stix_relationship_id: "relationship--3e3f06c4-3105-4d07-b876-702005e9b59a"
---
# Relationship 0516: M1041 — mitigates → T1003

**Source object:** [[01 ATT&CK/M1041 - Encrypt Sensitive Information|M1041: Encrypt Sensitive Information]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1003 - OS Credential Dumping|T1003: OS Credential Dumping]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Ensure Domain Controller backups are properly secured.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3e3f06c4-3105-4d07-b876-702005e9b59a`.
