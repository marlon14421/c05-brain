---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0192"
target_object: "T1134.001"
stix_relationship_id: "relationship--d17517a1-f941-46a0-bcb6-d2a5b94cb24b"
---
# Relationship 8895: S0192 — uses → T1134.001

**Source object:** [[01 ATT&CK/S0192 - Pupy|S0192: Pupy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1134.001 - Token Impersonation-Theft|T1134.001: Token Impersonation/Theft]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Pupy](https://attack.mitre.org/software/S0192) can obtain a list of SIDs and provide the option for selecting process tokens to impersonate.(Citation: GitHub Pupy)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d17517a1-f941-46a0-bcb6-d2a5b94cb24b`.
