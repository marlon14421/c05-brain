---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0230"
target_object: "T1543.003"
stix_relationship_id: "relationship--1d3c31c2-6756-483a-8aee-736bac591c1a"
---
# Relationship 6012: S0230 — uses → T1543.003

**Source object:** [[01 ATT&CK/S0230 - ZeroT|S0230: ZeroT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1543.003 - Windows Service|T1543.003: Windows Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ZeroT](https://attack.mitre.org/software/S0230) can add a new service to ensure [PlugX](https://attack.mitre.org/software/S0013) persists on the system when delivered as another payload onto the system.(Citation: Proofpoint ZeroT Feb 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1d3c31c2-6756-483a-8aee-736bac591c1a`.
