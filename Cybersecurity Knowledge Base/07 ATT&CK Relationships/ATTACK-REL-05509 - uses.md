---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0069"
target_object: "T1102.001"
stix_relationship_id: "relationship--8b0e9de1-a7b0-479e-aee7-76f2549508c6"
---
# Relationship 5509: S0069 — uses → T1102.001

**Source object:** [[01 ATT&CK/S0069 - BLACKCOFFEE|S0069: BLACKCOFFEE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1102.001 - Dead Drop Resolver|T1102.001: Dead Drop Resolver]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BLACKCOFFEE](https://attack.mitre.org/software/S0069) uses Microsoft’s TechNet Web portal to obtain a dead drop resolver containing an encoded tag with the IP address of a command and control server.(Citation: FireEye APT17)(Citation: FireEye Periscope March 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8b0e9de1-a7b0-479e-aee7-76f2549508c6`.
