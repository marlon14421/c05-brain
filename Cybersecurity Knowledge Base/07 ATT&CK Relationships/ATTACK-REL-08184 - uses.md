---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1154"
target_object: "T1056.004"
stix_relationship_id: "relationship--15a63ae2-08d7-4771-9537-276835d7513f"
---
# Relationship 8184: S1154 — uses → T1056.004

**Source object:** [[01 ATT&CK/S1154 - VersaMem|S1154: VersaMem]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.004 - Credential API Hooking|T1056.004: Credential API Hooking]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[VersaMem](https://attack.mitre.org/software/S1154) hooked and overrided Versa's built-in authentication method, `setUserPassword`, to intercept plaintext credentials when submitted to the server.(Citation: Lumen Versa 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--15a63ae2-08d7-4771-9537-276835d7513f`.
