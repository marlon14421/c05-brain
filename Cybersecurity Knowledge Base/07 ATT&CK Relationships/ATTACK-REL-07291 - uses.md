---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1023"
target_object: "S1110"
stix_relationship_id: "relationship--6d3e3456-40c8-4079-8a40-459d051e354e"
---
# Relationship 7291: G1023 — uses → S1110

**Source object:** [[01 ATT&CK/G1023 - APT5|G1023: APT5]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S1110 - SLIGHTPULSE|S1110: SLIGHTPULSE]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Mandiant Pulse Secure Zero-Day April 2021)(Citation: Mandiant Pulse Secure Update May 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6d3e3456-40c8-4079-8a40-459d051e354e`.
