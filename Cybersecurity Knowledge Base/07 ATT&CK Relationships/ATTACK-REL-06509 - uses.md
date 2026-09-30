---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1144"
target_object: "T1071.001"
stix_relationship_id: "relationship--fbf8de30-cf6d-4420-b928-b0be01b1f3ed"
---
# Relationship 6509: S1144 — uses → T1071.001

**Source object:** [[01 ATT&CK/S1144 - FRP|S1144: FRP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FRP](https://attack.mitre.org/software/S1144) has the ability to use HTTP and HTTPS to enable the forwarding of requests for internal services via domain name.(Citation: FRP GitHub)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fbf8de30-cf6d-4420-b928-b0be01b1f3ed`.
