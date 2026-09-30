---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0062"
target_object: "T1082"
stix_relationship_id: "relationship--cd18fa85-3b0c-4201-b85d-92dfaf91eb5a"
---
# Relationship 4823: C0062 — uses → T1082

**Source object:** [[01 ATT&CK/C0062 - Anthropic AI-orchestrated Campaign|C0062: Anthropic AI-orchestrated Campaign]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During the [Anthropic AI-orchestrated Campaign](https://attack.mitre.org/campaigns/C0062), the adversary tasked Claude Code to query databases and systems in order to identify proprietary information, including system configurations and database types.(Citation: Anthropic AI Orchestrated Campaign NOV 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cd18fa85-3b0c-4201-b85d-92dfaf91eb5a`.
