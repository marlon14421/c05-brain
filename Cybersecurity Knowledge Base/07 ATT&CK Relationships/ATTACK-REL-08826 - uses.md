---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0696"
target_object: "T1069.001"
stix_relationship_id: "relationship--8f5db833-979f-43c1-a28c-8a9ef3bb7980"
---
# Relationship 8826: S0696 — uses → T1069.001

**Source object:** [[01 ATT&CK/S0696 - Flagpro|S0696: Flagpro]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1069.001 - Local Groups|T1069.001: Local Groups]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Flagpro](https://attack.mitre.org/software/S0696) has been used to execute the net localgroup administrators command on a targeted system.(Citation: NTT Security Flagpro new December 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8f5db833-979f-43c1-a28c-8a9ef3bb7980`.
