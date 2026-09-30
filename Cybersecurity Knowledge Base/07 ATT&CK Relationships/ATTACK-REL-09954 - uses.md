---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0677"
target_object: "T1556.007"
stix_relationship_id: "relationship--3691a1cd-c9d4-4492-b6c1-7ceb1b661758"
---
# Relationship 9954: S0677 — uses → T1556.007

**Source object:** [[01 ATT&CK/S0677 - AADInternals|S0677: AADInternals]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1556.007 - Hybrid Identity|T1556.007: Hybrid Identity]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[AADInternals](https://attack.mitre.org/software/S0677) can inject a malicious DLL (`PTASpy`) into the `AzureADConnectAuthenticationAgentService` to backdoor Azure AD Pass-Through Authentication.(Citation: AADInternals Azure AD On-Prem to Cloud)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3691a1cd-c9d4-4492-b6c1-7ceb1b661758`.
