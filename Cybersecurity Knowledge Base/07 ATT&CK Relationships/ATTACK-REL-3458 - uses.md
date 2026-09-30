---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0430"
target_object: "T1095"
stix_relationship_id: "relationship--40622bce-ea51-4744-9240-4a4c4bf83753"
---
# Relationship 3458: S0430 — uses → T1095

**Source object:** [[01 ATT&CK/S0430 - Winnti for Linux|S0430: Winnti for Linux]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1095 - Non-Application Layer Protocol|T1095: Non-Application Layer Protocol]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Winnti for Linux](https://attack.mitre.org/software/S0430) has used ICMP, custom TCP, and UDP in outbound communications.(Citation: Chronicle Winnti for Linux May 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--40622bce-ea51-4744-9240-4a4c4bf83753`.
