---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0002"
target_object: "T1098"
stix_relationship_id: "relationship--6e641c36-188b-480e-b177-e412cd000b34"
---
# Relationship 6195: S0002 — uses → T1098

**Source object:** [[01 ATT&CK/S0002 - Mimikatz|S0002: Mimikatz]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1098 - Account Manipulation|T1098: Account Manipulation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

The [Mimikatz](https://attack.mitre.org/software/S0002) credential dumper has been extended to include Skeleton Key domain controller authentication bypass functionality. The LSADUMP::ChangeNTLM and LSADUMP::SetNTLM modules can also manipulate the password hash of an account without knowing the clear text value.(Citation: Adsecurity Mimikatz Guide)(Citation: Metcalf 2015)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6e641c36-188b-480e-b177-e412cd000b34`.
