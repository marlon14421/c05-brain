---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0018"
target_object: "T1571"
stix_relationship_id: "relationship--42af62e7-3e38-46e7-ac70-c557f33d377d"
---
# Relationship 2903: C0018 — uses → T1571

**Source object:** [[01 ATT&CK/C0018 - C0018|C0018: C0018]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1571 - Non-Standard Port|T1571: Non-Standard Port]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [C0018](https://attack.mitre.org/campaigns/C0018), the threat actors opened a variety of ports, including ports 28035, 32467, 41578, and 46892, to establish RDP connections.(Citation: Costa AvosLocker May 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--42af62e7-3e38-46e7-ac70-c557f33d377d`.
