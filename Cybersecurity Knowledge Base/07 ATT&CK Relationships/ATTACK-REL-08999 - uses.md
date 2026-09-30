---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0133"
target_object: "T1036"
stix_relationship_id: "relationship--3cc1b62f-5059-4fb1-be06-72bb13498002"
---
# Relationship 8999: G0133 — uses → T1036

**Source object:** [[01 ATT&CK/G0133 - Nomadic Octopus|G0133: Nomadic Octopus]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036 - Masquerading|T1036: Masquerading]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Nomadic Octopus](https://attack.mitre.org/groups/G0133) attempted to make [Octopus](https://attack.mitre.org/software/S0340) appear as a Telegram Messenger with a Russian interface.(Citation: Securelist Octopus Oct 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3cc1b62f-5059-4fb1-be06-72bb13498002`.
