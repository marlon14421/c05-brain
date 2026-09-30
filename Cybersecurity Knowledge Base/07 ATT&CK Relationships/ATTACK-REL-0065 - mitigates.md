---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1041"
target_object: "T1114.002"
stix_relationship_id: "relationship--8178dba2-1469-4322-af59-f6935152deb0"
---
# Relationship 0065: M1041 — mitigates → T1114.002

**Source object:** [[01 ATT&CK/M1041 - Encrypt Sensitive Information|M1041: Encrypt Sensitive Information]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1114.002 - Remote Email Collection|T1114.002: Remote Email Collection]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Use of encryption provides an added layer of security to sensitive information sent over email. Encryption using public key cryptography requires the adversary to obtain the private certificate along with an encryption key to decrypt messages.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8178dba2-1469-4322-af59-f6935152deb0`.
