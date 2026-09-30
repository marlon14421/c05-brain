---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0592"
target_object: "T1105"
stix_relationship_id: "relationship--e39a9d68-162f-45a3-b7c2-5914dd900b73"
---
# Relationship 6007: S0592 — uses → T1105

**Source object:** [[01 ATT&CK/S0592 - RemoteUtilities|S0592: RemoteUtilities]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RemoteUtilities](https://attack.mitre.org/software/S0592) can upload and download files to and from a target machine.(Citation: Trend Micro Muddy Water March 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e39a9d68-162f-45a3-b7c2-5914dd900b73`.
