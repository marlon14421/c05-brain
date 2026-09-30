---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1041"
target_object: "T1669"
stix_relationship_id: "relationship--be61d574-ada4-4575-85ed-0665905fa7e0"
---
# Relationship 1073: M1041 — mitigates → T1669

**Source object:** [[01 ATT&CK/M1041 - Encrypt Sensitive Information|M1041: Encrypt Sensitive Information]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1669 - Wi-Fi Networks|T1669: Wi-Fi Networks]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Ensure that all wired and/or wireless traffic is encrypted appropriately. Use best practices for authentication protocols, such as Kerberos, and ensure that web traffic that may contain credentials is protected by SSL/TLS.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--be61d574-ada4-4575-85ed-0665905fa7e0`.
