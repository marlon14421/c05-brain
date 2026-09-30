---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0636"
target_object: "T1105"
stix_relationship_id: "relationship--8972de3e-d073-47ec-9665-a10896601e12"
---
# Relationship 5066: S0636 — uses → T1105

**Source object:** [[01 ATT&CK/S0636 - VaporRage|S0636: VaporRage]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[VaporRage](https://attack.mitre.org/software/S0636) has the ability to download malicious shellcode to compromised systems.(Citation: MSTIC Nobelium Toolset May 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8972de3e-d073-47ec-9665-a10896601e12`.
