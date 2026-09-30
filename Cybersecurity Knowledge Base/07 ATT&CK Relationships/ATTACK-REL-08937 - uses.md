---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0126"
target_object: "T1071.001"
stix_relationship_id: "relationship--71db51a2-9968-408c-91b3-8f42a61d0b09"
---
# Relationship 8937: G0126 — uses → T1071.001

**Source object:** [[01 ATT&CK/G0126 - Higaisa|G0126: Higaisa]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Higaisa](https://attack.mitre.org/groups/G0126) used HTTP and HTTPS to send data back to its C2 server.(Citation: Malwarebytes Higaisa 2020)(Citation: Zscaler Higaisa 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--71db51a2-9968-408c-91b3-8f42a61d0b09`.
