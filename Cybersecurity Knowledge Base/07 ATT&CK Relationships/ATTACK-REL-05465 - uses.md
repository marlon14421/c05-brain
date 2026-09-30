---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0371"
target_object: "T1071.001"
stix_relationship_id: "relationship--3c98448a-15ec-4a51-8c41-8f1379d2dc0a"
---
# Relationship 5465: S0371 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0371 - POWERTON|S0371: POWERTON]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[POWERTON](https://attack.mitre.org/software/S0371) has used HTTP/HTTPS for C2 traffic.(Citation: FireEye APT33 Guardrail)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3c98448a-15ec-4a51-8c41-8f1379d2dc0a`.
