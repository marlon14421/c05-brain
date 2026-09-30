---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1018"
target_object: "T1199"
stix_relationship_id: "relationship--a42398e2-3daa-452a-80f8-f06660328f18"
---
# Relationship 0556: M1018 — mitigates → T1199

**Source object:** [[01 ATT&CK/M1018 - User Account Management|M1018: User Account Management]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1199 - Trusted Relationship|T1199: Trusted Relationship]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Properly manage accounts and permissions used by parties in trusted relationships to minimize potential abuse by the party and if the party is compromised by an adversary. In Office 365 environments, partner relationships and roles can be viewed under the “Partner Relationships” page.(Citation: Office 365 Partner Relationships)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a42398e2-3daa-452a-80f8-f06660328f18`.
