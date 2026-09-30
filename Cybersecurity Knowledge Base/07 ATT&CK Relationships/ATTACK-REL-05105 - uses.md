---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0018"
target_object: "T1007"
stix_relationship_id: "relationship--09c10778-19ad-441a-8a75-a3cf1288f960"
---
# Relationship 5105: S0018 — uses → T1007

**Source object:** [[01 ATT&CK/S0018 - Sykipot|S0018: Sykipot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1007 - System Service Discovery|T1007: System Service Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Sykipot](https://attack.mitre.org/software/S0018) may use net start to display running services.(Citation: AlienVault Sykipot 2011)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--09c10778-19ad-441a-8a75-a3cf1288f960`.
