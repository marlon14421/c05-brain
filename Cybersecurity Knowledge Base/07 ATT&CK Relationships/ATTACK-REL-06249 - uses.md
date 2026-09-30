---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1112"
target_object: "T1505.003"
stix_relationship_id: "relationship--63d2756f-21af-420d-beaa-a334cb213e80"
---
# Relationship 6249: S1112 — uses → T1505.003

**Source object:** [[01 ATT&CK/S1112 - STEADYPULSE|S1112: STEADYPULSE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1505.003 - Web Shell|T1505.003: Web Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[STEADYPULSE](https://attack.mitre.org/software/S1112) is a web shell that can enable the execution of arbitrary commands on compromised web servers.(Citation: Mandiant Pulse Secure Zero-Day April 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--63d2756f-21af-420d-beaa-a334cb213e80`.
