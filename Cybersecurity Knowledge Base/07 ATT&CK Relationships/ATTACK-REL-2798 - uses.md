---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0624"
target_object: "T1105"
stix_relationship_id: "relationship--eda15dd3-2e7d-470c-8b1d-227c7d877e67"
---
# Relationship 2798: S0624 — uses → T1105

**Source object:** [[01 ATT&CK/S0624 - Ecipekac|S0624: Ecipekac]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Ecipekac](https://attack.mitre.org/software/S0624) can download additional payloads to a compromised host.(Citation: Securelist APT10 March 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--eda15dd3-2e7d-470c-8b1d-227c7d877e67`.
