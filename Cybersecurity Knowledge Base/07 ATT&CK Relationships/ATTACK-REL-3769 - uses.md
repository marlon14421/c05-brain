---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0007"
target_object: "T1016"
stix_relationship_id: "relationship--7b553858-ffee-4817-9033-b9ea06f71d43"
---
# Relationship 3769: C0007 — uses → T1016

**Source object:** [[01 ATT&CK/C0007 - FunnyDream|C0007: FunnyDream]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [FunnyDream](https://attack.mitre.org/campaigns/C0007), the threat actors used [ipconfig](https://attack.mitre.org/software/S0100) for discovery on remote systems.(Citation: Bitdefender FunnyDream Campaign November 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7b553858-ffee-4817-9033-b9ea06f71d43`.
