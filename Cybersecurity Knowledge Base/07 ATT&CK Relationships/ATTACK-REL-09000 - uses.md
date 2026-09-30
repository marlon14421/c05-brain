---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0153"
target_object: "T1071.001"
stix_relationship_id: "relationship--c33c2a0f-eb88-43ef-be7b-6311bef2da3d"
---
# Relationship 9000: S0153 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0153 - RedLeaves|S0153: RedLeaves]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RedLeaves](https://attack.mitre.org/software/S0153) can communicate to its C2 over HTTP and HTTPS if directed.(Citation: FireEye APT10 April 2017)(Citation: Accenture Hogfish April 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c33c2a0f-eb88-43ef-be7b-6311bef2da3d`.
