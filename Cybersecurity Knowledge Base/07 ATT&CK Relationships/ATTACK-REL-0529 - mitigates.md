---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1017"
target_object: "T1213.004"
stix_relationship_id: "relationship--73d139f6-f976-4a5d-950d-adb2f0f1d242"
---
# Relationship 0529: M1017 — mitigates → T1213.004

**Source object:** [[01 ATT&CK/M1017 - User Training|M1017: User Training]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1213.004 - Customer Relationship Management Software|T1213.004: Customer Relationship Management Software]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Develop and publish policies that define acceptable information to be stored in CRM databases and acceptable handling of customer data. Only store customer information required for business operations.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--73d139f6-f976-4a5d-950d-adb2f0f1d242`.
