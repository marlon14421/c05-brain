---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0062"
target_object: "T1584.004"
stix_relationship_id: "relationship--a3c7c24f-c630-4a0e-a095-8918a7092547"
---
# Relationship 7728: C0062 — uses → T1584.004

**Source object:** [[01 ATT&CK/C0062 - Anthropic AI-orchestrated Campaign|C0062: Anthropic AI-orchestrated Campaign]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1584.004 - Server|T1584.004: Server]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During the [Anthropic AI-orchestrated Campaign](https://attack.mitre.org/campaigns/C0062), the adversary operated dedicated penetration testing servers accessible via MCP to support remote command execution, simultaneous tool coordination, and persistent operational state maintenance across campaign sessions.(Citation: Anthropic AI Orchestrated Campaign NOV 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a3c7c24f-c630-4a0e-a095-8918a7092547`.
