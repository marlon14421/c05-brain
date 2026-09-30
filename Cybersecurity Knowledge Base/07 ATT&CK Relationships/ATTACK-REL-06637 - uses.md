---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1116"
target_object: "T1554"
stix_relationship_id: "relationship--1ec3f511-0684-4e13-90a0-d8d93a7279b0"
---
# Relationship 6637: S1116 — uses → T1554

**Source object:** [[01 ATT&CK/S1116 - WARPWIRE|S1116: WARPWIRE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1554 - Compromise Host Software Binary|T1554: Compromise Host Software Binary]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[WARPWIRE](https://attack.mitre.org/software/S1116) can embed itself into a legitimate file on compromised Ivanti Connect Secure VPNs.(Citation: Mandiant Cutting Edge January 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1ec3f511-0684-4e13-90a0-d8d93a7279b0`.
