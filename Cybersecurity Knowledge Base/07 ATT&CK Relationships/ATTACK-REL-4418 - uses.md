---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0677"
target_object: "T1590.001"
stix_relationship_id: "relationship--a3932823-51c8-402d-a7a7-ee31882fc48a"
---
# Relationship 4418: S0677 — uses → T1590.001

**Source object:** [[01 ATT&CK/S0677 - AADInternals|S0677: AADInternals]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1590.001 - Domain Properties|T1590.001: Domain Properties]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[AADInternals](https://attack.mitre.org/software/S0677) can gather information about a tenant’s domains using public Microsoft APIs.(Citation: AADInternals Documentation)(Citation: Azure AD Recon)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a3932823-51c8-402d-a7a7-ee31882fc48a`.
