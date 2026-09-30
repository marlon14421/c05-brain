---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0062"
target_object: "T1592.004"
stix_relationship_id: "relationship--c5cdae9b-22b6-4f35-a688-2e9ece0652ec"
---
# Relationship 9072: C0062 — uses → T1592.004

**Source object:** [[01 ATT&CK/C0062 - Anthropic AI-orchestrated Campaign|C0062: Anthropic AI-orchestrated Campaign]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1592.004 - Client Configurations|T1592.004: Client Configurations]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During the [Anthropic AI-orchestrated Campaign](https://attack.mitre.org/campaigns/C0062), the adversary leveraged Claude Code to gather details of high-value systems to include databases and workflow orchestration platforms.(Citation: Anthropic AI Orchestrated Campaign NOV 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c5cdae9b-22b6-4f35-a688-2e9ece0652ec`.
