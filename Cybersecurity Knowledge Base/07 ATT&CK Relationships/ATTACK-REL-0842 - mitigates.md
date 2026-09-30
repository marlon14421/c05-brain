---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1016"
target_object: "T1195.002"
stix_relationship_id: "relationship--f57f7e65-0017-45a2-9abd-db439a64ad45"
---
# Relationship 0842: M1016 — mitigates → T1195.002

**Source object:** [[01 ATT&CK/M1016 - Vulnerability Scanning|M1016: Vulnerability Scanning]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1195.002 - Compromise Software Supply Chain|T1195.002: Compromise Software Supply Chain]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Continuous monitoring of vulnerability sources and the use of automatic and manual code review tools should also be implemented as well.(Citation: OWASP Top 10)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f57f7e65-0017-45a2-9abd-db439a64ad45`.
