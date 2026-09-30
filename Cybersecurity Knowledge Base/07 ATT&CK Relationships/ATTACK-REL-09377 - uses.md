---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0527"
target_object: "T1105"
stix_relationship_id: "relationship--6213e3cf-c18e-47de-b281-07aa3c3179db"
---
# Relationship 9377: S0527 — uses → T1105

**Source object:** [[01 ATT&CK/S0527 - CSPY Downloader|S0527: CSPY Downloader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CSPY Downloader](https://attack.mitre.org/software/S0527) can download additional tools to a compromised host.(Citation: Cybereason Kimsuky November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6213e3cf-c18e-47de-b281-07aa3c3179db`.
