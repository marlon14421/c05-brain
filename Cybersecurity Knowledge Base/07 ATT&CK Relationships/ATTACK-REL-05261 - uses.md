---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9035"
target_object: "T1071.001"
stix_relationship_id: "relationship--1af945ec-f8bf-4aa9-9756-47e0d41690e3"
---
# Relationship 5261: S9035 — uses → T1071.001

**Source object:** [[01 ATT&CK/S9035 - LAMEHUG|S9035: LAMEHUG]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LAMEHUG](https://attack.mitre.org/software/S9035) can use HTTP POST requests to exfiltrate data from compromised hosts to C2.(Citation: Splunk LAMEHUG SEP 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1af945ec-f8bf-4aa9-9756-47e0d41690e3`.
