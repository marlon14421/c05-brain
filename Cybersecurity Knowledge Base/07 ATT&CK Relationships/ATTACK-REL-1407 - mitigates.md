---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1041"
target_object: "T1557"
stix_relationship_id: "relationship--0d891052-0c98-4d4a-8d1b-42a02f656eaf"
---
# Relationship 1407: M1041 — mitigates → T1557

**Source object:** [[01 ATT&CK/M1041 - Encrypt Sensitive Information|M1041: Encrypt Sensitive Information]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1557 - Adversary-in-the-Middle|T1557: Adversary-in-the-Middle]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Ensure that all wired and/or wireless traffic is encrypted appropriately. Use best practices for authentication protocols, such as Kerberos, and ensure web traffic that may contain credentials is protected by SSL/TLS.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0d891052-0c98-4d4a-8d1b-42a02f656eaf`.
