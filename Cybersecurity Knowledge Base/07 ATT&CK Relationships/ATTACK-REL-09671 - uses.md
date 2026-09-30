---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1209"
target_object: "T1071.001"
stix_relationship_id: "relationship--4dfb8cee-0807-46db-aba1-c7024037c712"
---
# Relationship 9671: S1209 — uses → T1071.001

**Source object:** [[01 ATT&CK/S1209 - Quick Assist|S1209: Quick Assist]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Quick Assist](https://attack.mitre.org/software/S1209) communicates over TCP 443 via HTTPS to a remote session server, under which RDP traffic is transferred.(Citation: Microsoft Quick Assist 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4dfb8cee-0807-46db-aba1-c7024037c712`.
