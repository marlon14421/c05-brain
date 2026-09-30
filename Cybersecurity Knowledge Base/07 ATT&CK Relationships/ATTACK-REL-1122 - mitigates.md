---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1015"
target_object: "T1552.006"
stix_relationship_id: "relationship--b3a191f3-59be-4457-ad5c-085ea0391bfe"
---
# Relationship 1122: M1015 — mitigates → T1552.006

**Source object:** [[01 ATT&CK/M1015 - Active Directory Configuration|M1015: Active Directory Configuration]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1552.006 - Group Policy Preferences|T1552.006: Group Policy Preferences]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Remove vulnerable Group Policy Preferences.(Citation: Microsoft MS14-025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b3a191f3-59be-4457-ad5c-085ea0391bfe`.
