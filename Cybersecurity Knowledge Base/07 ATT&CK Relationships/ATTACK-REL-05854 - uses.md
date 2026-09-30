---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1158"
target_object: "T1027.009"
stix_relationship_id: "relationship--d8ad5375-e46e-407f-9de2-e4d241383497"
---
# Relationship 5854: S1158 — uses → T1027.009

**Source object:** [[01 ATT&CK/S1158 - DUSTPAN|S1158: DUSTPAN]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.009 - Embedded Payloads|T1027.009: Embedded Payloads]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DUSTPAN](https://attack.mitre.org/software/S1158) decrypts and executes an embedded payload.(Citation: Google Cloud APT41 2024)(Citation: Google Cloud APT41 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d8ad5375-e46e-407f-9de2-e4d241383497`.
