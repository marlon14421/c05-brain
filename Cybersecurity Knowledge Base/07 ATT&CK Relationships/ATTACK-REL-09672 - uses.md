---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0367"
target_object: "T1134.001"
stix_relationship_id: "relationship--2b16958e-8c41-4342-87d8-f98b42548724"
---
# Relationship 9672: S0367 — uses → T1134.001

**Source object:** [[01 ATT&CK/S0367 - Emotet|S0367: Emotet]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1134.001 - Token Impersonation-Theft|T1134.001: Token Impersonation/Theft]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Emotet](https://attack.mitre.org/software/S0367) has the ability to duplicate the user’s token.(Citation: Binary Defense Emotes Wi-Fi Spreader) For example, [Emotet](https://attack.mitre.org/software/S0367) may use a variant of Google’s ProtoBuf to send messages that specify how code will be executed.(Citation: emotet_hc3_nov2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2b16958e-8c41-4342-87d8-f98b42548724`.
