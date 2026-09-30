---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0194"
target_object: "T1482"
stix_relationship_id: "relationship--ee2068ec-c520-476e-979f-3dea201d0b9e"
---
# Relationship 5104: S0194 — uses → T1482

**Source object:** [[01 ATT&CK/S0194 - PowerSploit|S0194: PowerSploit]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1482 - Domain Trust Discovery|T1482: Domain Trust Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PowerSploit](https://attack.mitre.org/software/S0194) has modules such as Get-NetDomainTrust and Get-NetForestTrust to enumerate domain and forest trusts.(Citation: GitHub PowerSploit May 2012)(Citation: PowerSploit Documentation)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ee2068ec-c520-476e-979f-3dea201d0b9e`.
