---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9036"
target_object: "T1134.001"
stix_relationship_id: "relationship--c6fd30bf-8d96-4da0-855d-84a05fae3be8"
---
# Relationship 3734: S9036 — uses → T1134.001

**Source object:** [[01 ATT&CK/S9036 - LP-Notes|S9036: LP-Notes]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1134.001 - Token Impersonation-Theft|T1134.001: Token Impersonation/Theft]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[LP-Notes](https://attack.mitre.org/software/S9036) has impersonated the security context of the taskhostw.exe process via the `ImpersonateLoggedOnUser` API.(Citation: ESET_MuddyWater_Dec2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c6fd30bf-8d96-4da0-855d-84a05fae3be8`.
