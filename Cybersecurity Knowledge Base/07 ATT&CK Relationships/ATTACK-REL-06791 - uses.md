---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0038"
target_object: "T1098.002"
stix_relationship_id: "relationship--39d843d6-a08f-4167-9b4a-25e36533b4be"
---
# Relationship 6791: C0038 — uses → T1098.002

**Source object:** [[01 ATT&CK/C0038 - HomeLand Justice|C0038: HomeLand Justice]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1098.002 - Additional Email Delegate Permissions|T1098.002: Additional Email Delegate Permissions]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [HomeLand Justice](https://attack.mitre.org/campaigns/C0038), threat actors added the `ApplicationImpersonation` management role to accounts under their control to impersonate users and take ownership of targeted mailboxes.(Citation: Microsoft Albanian Government Attacks September 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--39d843d6-a08f-4167-9b4a-25e36533b4be`.
