---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1013"
target_object: "T1195"
stix_relationship_id: "relationship--3c740c2b-293a-4f6b-98a8-dde4a215eea1"
---
# Relationship 0101: M1013 — mitigates → T1195

**Source object:** [[01 ATT&CK/M1013 - Application Developer Guidance|M1013: Application Developer Guidance]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1195 - Supply Chain Compromise|T1195: Supply Chain Compromise]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Application developers should be cautious when selecting third-party libraries to integrate into their application. Additionally, where possible, developers should lock software dependencies to specific versions rather than pulling the latest version on build.(Citation: Cider Security Top 10 CICD Security Risks)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3c740c2b-293a-4f6b-98a8-dde4a215eea1`.
