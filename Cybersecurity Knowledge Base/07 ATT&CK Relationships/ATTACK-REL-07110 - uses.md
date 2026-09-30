---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0007"
target_object: "T1098.002"
stix_relationship_id: "relationship--c75b8dfa-5980-4686-9d74-b0c92ce60274"
---
# Relationship 7110: G0007 — uses → T1098.002

**Source object:** [[01 ATT&CK/G0007 - APT28|G0007: APT28]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1098.002 - Additional Email Delegate Permissions|T1098.002: Additional Email Delegate Permissions]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT28](https://attack.mitre.org/groups/G0007) has used a Powershell cmdlet to grant the ApplicationImpersonation role to a compromised account.(Citation: Cybersecurity Advisory GRU Brute Force Campaign July 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c75b8dfa-5980-4686-9d74-b0c92ce60274`.
