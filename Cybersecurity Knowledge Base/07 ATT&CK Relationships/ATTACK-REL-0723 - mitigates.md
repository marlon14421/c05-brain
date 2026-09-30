---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1047"
target_object: "T1684"
stix_relationship_id: "relationship--87303a3c-4a04-4d0c-b382-104593054162"
---
# Relationship 0723: M1047 — mitigates → T1684

**Source object:** [[01 ATT&CK/M1047 - Audit|M1047: Audit]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1684 - Social Engineering|T1684: Social Engineering]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Enables correlation of email/identity/SaaS/endpoint activity that appears legitimate.(Citation: Proofpoint TA427 April 2024)(Citation: Unit 42 Global Incident Response Report 2026)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--87303a3c-4a04-4d0c-b382-104593054162`.
