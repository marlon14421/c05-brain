---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0018"
target_object: "T1055.001"
stix_relationship_id: "relationship--df5bee66-b840-405e-b9d5-2e0ced2e6808"
---
# Relationship 8385: S0018 — uses → T1055.001

**Source object:** [[01 ATT&CK/S0018 - Sykipot|S0018: Sykipot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.001 - Dynamic-link Library Injection|T1055.001: Dynamic-link Library Injection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Sykipot](https://attack.mitre.org/software/S0018) injects itself into running instances of outlook.exe, iexplore.exe, or firefox.exe.(Citation: AlienVault Sykipot 2011)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--df5bee66-b840-405e-b9d5-2e0ced2e6808`.
