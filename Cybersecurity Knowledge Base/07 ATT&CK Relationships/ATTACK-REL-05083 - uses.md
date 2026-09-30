---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0127"
target_object: "T1071.001"
stix_relationship_id: "relationship--7fd6c479-00ae-478d-a29b-fc40619eea97"
---
# Relationship 5083: S0127 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0127 - BBSRAT|S0127: BBSRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BBSRAT](https://attack.mitre.org/software/S0127) uses GET and POST requests over HTTP or HTTPS for command and control to obtain commands and send ZLIB compressed data back to the C2 server.(Citation: Palo Alto Networks BBSRAT)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7fd6c479-00ae-478d-a29b-fc40619eea97`.
