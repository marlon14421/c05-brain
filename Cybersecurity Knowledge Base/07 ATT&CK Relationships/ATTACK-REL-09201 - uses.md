---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0436"
target_object: "T1105"
stix_relationship_id: "relationship--1e54c837-6d59-40dc-a114-3bcef0037327"
---
# Relationship 9201: S0436 — uses → T1105

**Source object:** [[01 ATT&CK/S0436 - TSCookie|S0436: TSCookie]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TSCookie](https://attack.mitre.org/software/S0436) has the ability to upload and download files to and from the infected host.(Citation: JPCert TSCookie March 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1e54c837-6d59-40dc-a114-3bcef0037327`.
