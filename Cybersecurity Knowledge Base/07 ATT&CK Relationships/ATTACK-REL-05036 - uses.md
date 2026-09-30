---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0467"
target_object: "T1041"
stix_relationship_id: "relationship--655005cc-a289-4878-8dc0-64f0c7d167c4"
---
# Relationship 5036: S0467 — uses → T1041

**Source object:** [[01 ATT&CK/S0467 - TajMahal|S0467: TajMahal]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TajMahal](https://attack.mitre.org/software/S0467) has the ability to send collected files over its C2.(Citation: Kaspersky TajMahal April 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--655005cc-a289-4878-8dc0-64f0c7d167c4`.
