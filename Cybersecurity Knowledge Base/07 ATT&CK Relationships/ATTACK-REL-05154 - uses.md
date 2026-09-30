---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0045"
target_object: "T1071.001"
stix_relationship_id: "relationship--9a05a8cc-8d3c-46a5-947e-bebed2ab1c5a"
---
# Relationship 5154: S0045 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0045 - ADVSTORESHELL|S0045: ADVSTORESHELL]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ADVSTORESHELL](https://attack.mitre.org/software/S0045) connects to port 80 of a C2 server using Wininet API. Data is exchanged via HTTP POSTs.(Citation: Kaspersky Sofacy)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9a05a8cc-8d3c-46a5-947e-bebed2ab1c5a`.
