---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9042"
target_object: "T1677"
stix_relationship_id: "relationship--5ff41d73-f0e7-46e1-9d62-972b2a837ad0"
---
# Relationship 4996: S9042 — uses → T1677

**Source object:** [[01 ATT&CK/S9042 - CanisterWorm|S9042: CanisterWorm]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1677 - Poisoned Pipeline Execution|T1677: Poisoned Pipeline Execution]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[CanisterWorm](https://attack.mitre.org/software/S9042) has leveraged stolen tokens from Trivy users to publish itself across over 46 npm packages.(Citation: Aikido TeamPCP Telnyx MAR 2026)(Citation: Aikido TeamPCP Trivy MAR 2026)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5ff41d73-f0e7-46e1-9d62-972b2a837ad0`.
