---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0094"
target_object: "T1583.001"
stix_relationship_id: "relationship--5f601200-9fcd-44b7-96c2-5a2a1daea489"
---
# Relationship 5533: G0094 — uses → T1583.001

**Source object:** [[01 ATT&CK/G0094 - Kimsuky|G0094: Kimsuky]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1583.001 - Domains|T1583.001: Domains]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kimsuky](https://attack.mitre.org/groups/G0094) has registered domains to spoof targeted organizations and trusted third parties including search engines, web platforms, and cryptocurrency exchanges.(Citation: ThreatConnect Kimsuky September 2020)(Citation: Zdnet Kimsuky Group September 2020)(Citation: CISA AA20-301A Kimsuky)(Citation: Cybereason Kimsuky November 2020)(Citation: Malwarebytes Kimsuky June 2021)(Citation: KISA Operation Muzabi)(Citation: Mandiant APT43 March 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5f601200-9fcd-44b7-96c2-5a2a1daea489`.
