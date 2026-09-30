---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0140"
target_object: "T1134.001"
stix_relationship_id: "relationship--755bc45a-9048-4f58-b405-2ea8329328a1"
---
# Relationship 5147: S0140 — uses → T1134.001

**Source object:** [[01 ATT&CK/S0140 - Shamoon|S0140: Shamoon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1134.001 - Token Impersonation-Theft|T1134.001: Token Impersonation/Theft]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Shamoon](https://attack.mitre.org/software/S0140) can impersonate tokens using LogonUser , ImpersonateLoggedOnUser , and ImpersonateNamedPipeClient .(Citation: McAfee Shamoon December 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--755bc45a-9048-4f58-b405-2ea8329328a1`.
