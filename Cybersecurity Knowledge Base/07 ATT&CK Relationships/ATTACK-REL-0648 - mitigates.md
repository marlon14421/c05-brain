---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1013"
target_object: "T1195.001"
stix_relationship_id: "relationship--ef48b966-327f-4795-a1d0-4baf949fad2f"
---
# Relationship 0648: M1013 — mitigates → T1195.001

**Source object:** [[01 ATT&CK/M1013 - Application Developer Guidance|M1013: Application Developer Guidance]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1195.001 - Compromise Software Dependencies and Development Tools|T1195.001: Compromise Software Dependencies and Development Tools]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Application developers should be cautious when selecting third-party libraries to integrate into their application. Additionally, where possible, developers should lock software dependencies to specific versions rather than pulling the latest version on build.(Citation: Cider Security Top 10 CICD Security Risks) GitHub Actions may be pinned to a specific commit hash rather than a tag or branch.(Citation: Unit 42 Palo Alto GitHub Actions Supply Chain Attack 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ef48b966-327f-4795-a1d0-4baf949fad2f`.
