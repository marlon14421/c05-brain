---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1160"
target_object: "T1053.005"
stix_relationship_id: "relationship--35437cd0-280a-407d-9f3a-36dc61deba1a"
---
# Relationship 4549: S1160 — uses → T1053.005

**Source object:** [[01 ATT&CK/S1160 - Latrodectus|S1160: Latrodectus]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.005 - Scheduled Task|T1053.005: Scheduled Task]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Latrodectus](https://attack.mitre.org/software/S1160) can create scheduled tasks for persistence.(Citation: Latrodectus APR 2024)(Citation: Elastic Latrodectus May 2024)(Citation: Bitsight Latrodectus June 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--35437cd0-280a-407d-9f3a-36dc61deba1a`.
