---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1017"
target_object: "T1556.001"
stix_relationship_id: "relationship--bb30a4b2-90e2-4b29-87f8-f01654b487be"
---
# Relationship 1253: M1017 — mitigates → T1556.001

**Source object:** [[01 ATT&CK/M1017 - User Training|M1017: User Training]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1556.001 - Domain Controller Authentication|T1556.001: Domain Controller Authentication]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Train users to recognize and handle suspicious email attachments. Emphasize the importance of caution when opening attachments from unknown or unexpected sources, even if they appear legitimate. Implement email warning banners to alert users about emails originating from outside the organization or containing attachments, reinforcing awareness and helping users identify potential spearphishing attempts.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bb30a4b2-90e2-4b29-87f8-f01654b487be`.
