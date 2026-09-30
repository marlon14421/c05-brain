---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0687"
target_object: "T1071.001"
stix_relationship_id: "relationship--e597058d-ca4b-48e8-b924-8f1e8db34dc0"
---
# Relationship 5596: S0687 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0687 - Cyclops Blink|S0687: Cyclops Blink]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Cyclops Blink](https://attack.mitre.org/software/S0687) can download files via HTTP and HTTPS.(Citation: NCSC Cyclops Blink February 2022)(Citation: Trend Micro Cyclops Blink March 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e597058d-ca4b-48e8-b924-8f1e8db34dc0`.
