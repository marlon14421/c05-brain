---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0062"
target_object: "T1049"
stix_relationship_id: "relationship--ecdd4a9f-c89b-444f-ae27-c51c5714b60c"
---
# Relationship 4433: C0062 — uses → T1049

**Source object:** [[01 ATT&CK/C0062 - Anthropic AI-orchestrated Campaign|C0062: Anthropic AI-orchestrated Campaign]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1049 - System Network Connections Discovery|T1049: System Network Connections Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During the [Anthropic AI-orchestrated Campaign](https://attack.mitre.org/campaigns/C0062), the adversary used Claude Code to map internal network architecture and access relationships.(Citation: Anthropic AI Orchestrated Campaign NOV 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ecdd4a9f-c89b-444f-ae27-c51c5714b60c`.
