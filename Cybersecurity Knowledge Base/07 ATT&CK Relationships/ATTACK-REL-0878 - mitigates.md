---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1051"
target_object: "T1203"
stix_relationship_id: "relationship--c8f99f79-c0da-4767-8191-34cf2012b559"
---
# Relationship 0878: M1051 — mitigates → T1203

**Source object:** [[01 ATT&CK/M1051 - Update Software|M1051: Update Software]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1203 - Exploitation for Client Execution|T1203: Exploitation for Client Execution]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Perform regular software updates to mitigate exploitation risk. Keeping software up-to-date with the latest security patches helps prevent adversaries from exploiting known vulnerabilities in client software, reducing the risk of successful attacks.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c8f99f79-c0da-4767-8191-34cf2012b559`.
