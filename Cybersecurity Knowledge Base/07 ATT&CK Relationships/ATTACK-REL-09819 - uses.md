---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0589"
target_object: "T1218.011"
stix_relationship_id: "relationship--bdb9f6a6-7fe0-47e5-b708-3cb92360f6f9"
---
# Relationship 9819: S0589 — uses → T1218.011

**Source object:** [[01 ATT&CK/S0589 - Sibot|S0589: Sibot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.011 - Rundll32|T1218.011: Rundll32]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Sibot](https://attack.mitre.org/software/S0589) has executed downloaded DLLs with rundll32.exe .(Citation: MSTIC NOBELIUM Mar 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bdb9f6a6-7fe0-47e5-b708-3cb92360f6f9`.
