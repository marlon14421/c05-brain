---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1105"
target_object: "T1071.001"
stix_relationship_id: "relationship--abb92b2c-4211-48fd-b446-d94c18e58d62"
---
# Relationship 5584: S1105 — uses → T1071.001

**Source object:** [[01 ATT&CK/S1105 - COATHANGER|S1105: COATHANGER]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[COATHANGER](https://attack.mitre.org/software/S1105) uses an HTTP GET request to initialize a follow-on TLS tunnel for command and control.(Citation: NCSC-NL COATHANGER Feb 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--abb92b2c-4211-48fd-b446-d94c18e58d62`.
