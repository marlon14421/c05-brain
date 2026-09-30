---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1160"
target_object: "T1047"
stix_relationship_id: "relationship--e7995f43-d3f1-4ad2-b3bd-fc835faa3333"
---
# Relationship 8936: S1160 — uses → T1047

**Source object:** [[01 ATT&CK/S1160 - Latrodectus|S1160: Latrodectus]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1047 - Windows Management Instrumentation|T1047: Windows Management Instrumentation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Latrodectus](https://attack.mitre.org/software/S1160) has used WMI in malicious email infection chains to facilitate the installation of remotely-hosted files.(Citation: Elastic Latrodectus May 2024)(Citation: Bitsight Latrodectus June 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e7995f43-d3f1-4ad2-b3bd-fc835faa3333`.
