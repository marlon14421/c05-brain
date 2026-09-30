---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0696"
target_object: "T1018"
stix_relationship_id: "relationship--8c155a65-b89f-44aa-b4c0-1374208a3fed"
---
# Relationship 7915: S0696 — uses → T1018

**Source object:** [[01 ATT&CK/S0696 - Flagpro|S0696: Flagpro]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1018 - Remote System Discovery|T1018: Remote System Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Flagpro](https://attack.mitre.org/software/S0696) has been used to execute net view on a targeted system.(Citation: NTT Security Flagpro new December 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8c155a65-b89f-44aa-b4c0-1374208a3fed`.
