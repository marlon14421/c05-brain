---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0622"
target_object: "T1071.001"
stix_relationship_id: "relationship--c223714e-1321-45e2-b5e2-2b54959d340a"
---
# Relationship 4002: S0622 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0622 - AppleSeed|S0622: AppleSeed]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[AppleSeed](https://attack.mitre.org/software/S0622) has the ability to communicate with C2 over HTTP.(Citation: Malwarebytes Kimsuky June 2021)(Citation: KISA Operation Muzabi)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c223714e-1321-45e2-b5e2-2b54959d340a`.
