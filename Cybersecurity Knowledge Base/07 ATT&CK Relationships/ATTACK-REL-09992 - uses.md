---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1023"
target_object: "S1104"
stix_relationship_id: "relationship--63aca7d8-64dc-412b-a8ab-8af712fd4d82"
---
# Relationship 9992: G1023 — uses → S1104

**Source object:** [[01 ATT&CK/G1023 - APT5|G1023: APT5]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S1104 - SLOWPULSE|S1104: SLOWPULSE]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Mandiant Pulse Secure Zero-Day April 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--63aca7d8-64dc-412b-a8ab-8af712fd4d82`.
