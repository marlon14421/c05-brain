---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0096"
target_object: "S1158"
stix_relationship_id: "relationship--662fc68e-d956-4ee5-8adc-e0cc37470f8f"
---
# Relationship 5054: G0096 — uses → S1158

**Source object:** [[01 ATT&CK/G0096 - APT41|G0096: APT41]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S1158 - DUSTPAN|S1158: DUSTPAN]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DUSTPAN](https://attack.mitre.org/software/S1158) has been used by [APT41](https://attack.mitre.org/groups/G0096) in various campaigns since at least 2021.(Citation: Google Cloud APT41 2022)(Citation: Google Cloud APT41 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--662fc68e-d956-4ee5-8adc-e0cc37470f8f`.
