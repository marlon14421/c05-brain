---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0062"
target_object: "T1592.002"
stix_relationship_id: "relationship--3dad2d50-94ce-4280-b3db-56286642c14b"
---
# Relationship 8515: C0062 — uses → T1592.002

**Source object:** [[01 ATT&CK/C0062 - Anthropic AI-orchestrated Campaign|C0062: Anthropic AI-orchestrated Campaign]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1592.002 - Software|T1592.002: Software]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During the [Anthropic AI-orchestrated Campaign](https://attack.mitre.org/campaigns/C0062), the adversary utilized Claude Code to catalog services and data on discovered endpoints.(Citation: Anthropic AI Orchestrated Campaign NOV 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3dad2d50-94ce-4280-b3db-56286642c14b`.
