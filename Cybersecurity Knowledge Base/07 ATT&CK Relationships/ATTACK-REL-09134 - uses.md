---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0093"
target_object: "T1105"
stix_relationship_id: "relationship--e1268feb-9326-40e1-b05b-fd8e0068488a"
---
# Relationship 9134: G0093 — uses → T1105

**Source object:** [[01 ATT&CK/G0093 - GALLIUM|G0093: GALLIUM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[GALLIUM](https://attack.mitre.org/groups/G0093) dropped additional tools to victims during their operation, including portqry.exe, a renamed cmd.exe file, winrar, and [HTRAN](https://attack.mitre.org/software/S0040).(Citation: Cybereason Soft Cell June 2019)(Citation: Microsoft GALLIUM December 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e1268feb-9326-40e1-b05b-fd8e0068488a`.
