---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0038"
target_object: "T1134.001"
stix_relationship_id: "relationship--45a8a431-8465-4f6e-8258-817d919a6a52"
---
# Relationship 9743: C0038 — uses → T1134.001

**Source object:** [[01 ATT&CK/C0038 - HomeLand Justice|C0038: HomeLand Justice]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1134.001 - Token Impersonation-Theft|T1134.001: Token Impersonation/Theft]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [HomeLand Justice](https://attack.mitre.org/campaigns/C0038), threat actors used custom tooling to acquire tokens using `ImpersonateLoggedOnUser/SetThreadToken`.(Citation: Microsoft Albanian Government Attacks September 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--45a8a431-8465-4f6e-8258-817d919a6a52`.
