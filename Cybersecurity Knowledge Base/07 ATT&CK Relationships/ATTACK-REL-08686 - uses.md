---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0201"
target_object: "T1016"
stix_relationship_id: "relationship--264e85a3-1ddc-4b68-87fc-c2b96d6ec0e9"
---
# Relationship 8686: S0201 — uses → T1016

**Source object:** [[01 ATT&CK/S0201 - JPIN|S0201: JPIN]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[JPIN](https://attack.mitre.org/software/S0201) can obtain network information, including DNS, IP, and proxies.(Citation: Microsoft PLATINUM April 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--264e85a3-1ddc-4b68-87fc-c2b96d6ec0e9`.
