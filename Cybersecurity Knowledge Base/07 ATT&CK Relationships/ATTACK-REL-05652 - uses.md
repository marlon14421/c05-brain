---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0538"
target_object: "T1071.001"
stix_relationship_id: "relationship--1ca96a8d-898b-4778-b3c3-3c80ccbb407f"
---
# Relationship 5652: S0538 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0538 - Crutch|S0538: Crutch]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Crutch](https://attack.mitre.org/software/S0538) has conducted C2 communications with a Dropbox account using the HTTP API.(Citation: ESET Crutch December 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1ca96a8d-898b-4778-b3c3-3c80ccbb407f`.
