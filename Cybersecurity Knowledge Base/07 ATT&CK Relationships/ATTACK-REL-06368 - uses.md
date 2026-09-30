---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1108"
target_object: "T1132.001"
stix_relationship_id: "relationship--8a6b0a59-a9f7-4e65-8070-303a6b79e6bb"
---
# Relationship 6368: S1108 — uses → T1132.001

**Source object:** [[01 ATT&CK/S1108 - PULSECHECK|S1108: PULSECHECK]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1132.001 - Standard Encoding|T1132.001: Standard Encoding]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PULSECHECK](https://attack.mitre.org/software/S1108) can base-64 encode encrypted data sent through C2.(Citation: Mandiant Pulse Secure Zero-Day April 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8a6b0a59-a9f7-4e65-8070-303a6b79e6bb`.
