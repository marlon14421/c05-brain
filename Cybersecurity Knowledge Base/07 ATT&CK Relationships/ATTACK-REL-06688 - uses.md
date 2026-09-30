---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0262"
target_object: "T1105"
stix_relationship_id: "relationship--4a33da76-c838-48fe-97ad-80d285cf165f"
---
# Relationship 6688: S0262 — uses → T1105

**Source object:** [[01 ATT&CK/S0262 - QuasarRAT|S0262: QuasarRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[QuasarRAT](https://attack.mitre.org/software/S0262) can download files to the victim’s machine and execute them.(Citation: GitHub QuasarRAT)(Citation: Volexity Patchwork June 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4a33da76-c838-48fe-97ad-80d285cf165f`.
