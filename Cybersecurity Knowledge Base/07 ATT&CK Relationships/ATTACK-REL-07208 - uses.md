---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1110"
target_object: "T1132.001"
stix_relationship_id: "relationship--329f545d-7ef4-4c43-9ce8-b56e7275e11f"
---
# Relationship 7208: S1110 — uses → T1132.001

**Source object:** [[01 ATT&CK/S1110 - SLIGHTPULSE|S1110: SLIGHTPULSE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1132.001 - Standard Encoding|T1132.001: Standard Encoding]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SLIGHTPULSE](https://attack.mitre.org/software/S1110) can base64 encode all incoming and outgoing C2 messages.(Citation: Mandiant Pulse Secure Zero-Day April 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--329f545d-7ef4-4c43-9ce8-b56e7275e11f`.
