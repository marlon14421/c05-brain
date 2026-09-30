---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0445"
target_object: "T1087"
stix_relationship_id: "relationship--52741f41-28c6-4533-bd26-6dc21f6b0794"
---
# Relationship 9532: S0445 — uses → T1087

**Source object:** [[01 ATT&CK/S0445 - ShimRatReporter|S0445: ShimRatReporter]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1087 - Account Discovery|T1087: Account Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ShimRatReporter](https://attack.mitre.org/software/S0445) listed all non-privileged and privileged accounts available on the machine.(Citation: FOX-IT May 2016 Mofang)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--52741f41-28c6-4533-bd26-6dc21f6b0794`.
