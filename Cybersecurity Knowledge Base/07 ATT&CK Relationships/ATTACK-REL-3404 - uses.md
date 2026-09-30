---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0043"
target_object: "T1571"
stix_relationship_id: "relationship--d00a3ec5-cdbf-4646-a12e-4269dce56774"
---
# Relationship 3404: C0043 — uses → T1571

**Source object:** [[01 ATT&CK/C0043 - Indian Critical Infrastructure Intrusions|C0043: Indian Critical Infrastructure Intrusions]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1571 - Non-Standard Port|T1571: Non-Standard Port]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [Indian Critical Infrastructure Intrusions](https://attack.mitre.org/campaigns/C0043), [RedEcho](https://attack.mitre.org/groups/G1042) used non-standard ports such as TCP 8080 for HTTP communication.(Citation: RecordedFuture RedEcho 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d00a3ec5-cdbf-4646-a12e-4269dce56774`.
