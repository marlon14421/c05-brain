---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0594"
target_object: "T1114.001"
stix_relationship_id: "relationship--c69d17b1-c261-44c6-9da5-c310cf20f91b"
---
# Relationship 9884: S0594 — uses → T1114.001

**Source object:** [[01 ATT&CK/S0594 - Out1|S0594: Out1]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1114.001 - Local Email Collection|T1114.001: Local Email Collection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Out1](https://attack.mitre.org/software/S0594) can parse e-mails on a target machine.(Citation: Trend Micro Muddy Water March 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c69d17b1-c261-44c6-9da5-c310cf20f91b`.
