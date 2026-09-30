---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0230"
target_object: "T1105"
stix_relationship_id: "relationship--bff3220c-6fea-4925-a9d0-46f06efb7337"
---
# Relationship 7503: S0230 — uses → T1105

**Source object:** [[01 ATT&CK/S0230 - ZeroT|S0230: ZeroT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ZeroT](https://attack.mitre.org/software/S0230) can download additional payloads onto the victim.(Citation: Proofpoint ZeroT Feb 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bff3220c-6fea-4925-a9d0-46f06efb7337`.
