---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0061"
target_object: "T1018"
stix_relationship_id: "relationship--6efce751-f7b8-4918-b80d-a6c77237516b"
---
# Relationship 4813: C0061 — uses → T1018

**Source object:** [[01 ATT&CK/C0061 - Operation Digital Eye|C0061: Operation Digital Eye]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1018 - Remote System Discovery|T1018: Remote System Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [Operation Digital Eye](https://attack.mitre.org/campaigns/C0061), threat actors used [Ping](https://attack.mitre.org/software/S0097) for reconnaissance.(Citation: sentinelone operationDigitalEye Dec 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6efce751-f7b8-4918-b80d-a6c77237516b`.
