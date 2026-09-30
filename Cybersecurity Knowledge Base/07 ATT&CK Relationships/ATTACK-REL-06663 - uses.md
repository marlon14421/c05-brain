---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0072"
target_object: "T1071.001"
stix_relationship_id: "relationship--d53d1e84-f4de-4e6a-bc84-5edfce84b055"
---
# Relationship 6663: S0072 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0072 - OwaAuth|S0072: OwaAuth]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[OwaAuth](https://attack.mitre.org/software/S0072) uses incoming HTTP requests with a username keyword and commands and handles them as instructions to perform actions.(Citation: Dell TG-3390)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d53d1e84-f4de-4e6a-bc84-5edfce84b055`.
