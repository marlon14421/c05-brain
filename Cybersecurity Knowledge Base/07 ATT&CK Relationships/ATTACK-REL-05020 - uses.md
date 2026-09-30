---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0379"
target_object: "T1123"
stix_relationship_id: "relationship--ade8894f-e9fd-4391-98c3-d43ad2d7ab9c"
---
# Relationship 5020: S0379 — uses → T1123

**Source object:** [[01 ATT&CK/S0379 - Revenge RAT|S0379: Revenge RAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1123 - Audio Capture|T1123: Audio Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Revenge RAT](https://attack.mitre.org/software/S0379) has a plugin for microphone interception.(Citation: Cylance Shaheen Nov 2018)(Citation: Cofense RevengeRAT Feb 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ade8894f-e9fd-4391-98c3-d43ad2d7ab9c`.
