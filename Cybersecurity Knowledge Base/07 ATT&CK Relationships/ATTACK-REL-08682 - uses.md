---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1115"
target_object: "T1505.003"
stix_relationship_id: "relationship--2856ba71-fa3d-4aa7-99ae-3438f11b2655"
---
# Relationship 8682: S1115 — uses → T1505.003

**Source object:** [[01 ATT&CK/S1115 - WIREFIRE|S1115: WIREFIRE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1505.003 - Web Shell|T1505.003: Web Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[WIREFIRE](https://attack.mitre.org/software/S1115) is a web shell that can download files to and execute arbitrary commands from compromised Ivanti Connect Secure VPNs.(Citation: Mandiant Cutting Edge January 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2856ba71-fa3d-4aa7-99ae-3438f11b2655`.
