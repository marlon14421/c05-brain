---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0080"
target_object: "T1003.002"
stix_relationship_id: "relationship--ac72c3da-6b58-4f66-8476-8d3cc9ccf6bd"
---
# Relationship 6107: S0080 — uses → T1003.002

**Source object:** [[01 ATT&CK/S0080 - Mivast|S0080: Mivast]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1003.002 - Security Account Manager|T1003.002: Security Account Manager]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mivast](https://attack.mitre.org/software/S0080) has the capability to gather NTLM password information.(Citation: Symantec Backdoor.Mivast)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ac72c3da-6b58-4f66-8476-8d3cc9ccf6bd`.
