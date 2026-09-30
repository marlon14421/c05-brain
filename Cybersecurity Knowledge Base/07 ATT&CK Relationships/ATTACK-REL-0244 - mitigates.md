---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1032"
target_object: "T1114.002"
stix_relationship_id: "relationship--854e11fd-f29e-4b7e-a3c2-f4c8c9ee302f"
---
# Relationship 0244: M1032 — mitigates → T1114.002

**Source object:** [[01 ATT&CK/M1032 - Multi-factor Authentication|M1032: Multi-factor Authentication]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1114.002 - Remote Email Collection|T1114.002: Remote Email Collection]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Use of multi-factor authentication for public-facing webmail servers is a recommended best practice to minimize the usefulness of usernames and passwords to adversaries.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--854e11fd-f29e-4b7e-a3c2-f4c8c9ee302f`.
