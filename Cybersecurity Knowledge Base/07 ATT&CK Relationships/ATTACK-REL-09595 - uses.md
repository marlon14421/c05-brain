---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0046"
target_object: "T1556"
stix_relationship_id: "relationship--a3659b6e-9588-4b4c-aca0-32282f96167f"
---
# Relationship 9595: C0046 — uses → T1556

**Source object:** [[01 ATT&CK/C0046 - ArcaneDoor|C0046: ArcaneDoor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1556 - Modify Authentication Process|T1556: Modify Authentication Process]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ArcaneDoor](https://attack.mitre.org/campaigns/C0046) included modification of the AAA process to bypass authentication mechanisms.(Citation: Cisco ArcaneDoor 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a3659b6e-9588-4b4c-aca0-32282f96167f`.
