---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1050"
target_object: "T1190"
stix_relationship_id: "relationship--53a95297-1cce-401c-99a3-34079e878fac"
---
# Relationship 1225: M1050 — mitigates → T1190

**Source object:** [[01 ATT&CK/M1050 - Exploit Protection|M1050: Exploit Protection]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1190 - Exploit Public-Facing Application|T1190: Exploit Public-Facing Application]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Web Application Firewalls may be used to limit exposure of applications to prevent exploit traffic from reaching the application.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--53a95297-1cce-401c-99a3-34079e878fac`.
