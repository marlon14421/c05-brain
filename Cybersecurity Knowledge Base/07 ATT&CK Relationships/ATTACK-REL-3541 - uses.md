---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0496"
target_object: "T1105"
stix_relationship_id: "relationship--a910e0f8-1548-4dd6-a0eb-19430a5f75b0"
---
# Relationship 3541: S0496 — uses → T1105

**Source object:** [[01 ATT&CK/S0496 - REvil|S0496: REvil]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[REvil](https://attack.mitre.org/software/S0496) can download a copy of itself from an attacker controlled IP address to the victim machine.(Citation: Talos Sodinokibi April 2019)(Citation: McAfee Sodinokibi October 2019)(Citation: Picus Sodinokibi January 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a910e0f8-1548-4dd6-a0eb-19430a5f75b0`.
