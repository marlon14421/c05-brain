---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0062"
target_object: "T1087"
stix_relationship_id: "relationship--764862c1-bef5-45e0-9985-3fcae340cb9f"
---
# Relationship 4001: C0062 — uses → T1087

**Source object:** [[01 ATT&CK/C0062 - Anthropic AI-orchestrated Campaign|C0062: Anthropic AI-orchestrated Campaign]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1087 - Account Discovery|T1087: Account Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During the [Anthropic AI-orchestrated Campaign](https://attack.mitre.org/campaigns/C0062), the adversary used Claude Code to query internal database user account tables to enumerate accounts and identify high-privilege accounts within compromised environments.(Citation: Anthropic AI Orchestrated Campaign NOV 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--764862c1-bef5-45e0-9985-3fcae340cb9f`.
