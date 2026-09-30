---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0481"
target_object: "T1489"
stix_relationship_id: "relationship--9212f940-021e-49b1-b500-fa1dd76b7132"
---
# Relationship 3448: S0481 — uses → T1489

**Source object:** [[01 ATT&CK/S0481 - Ragnar Locker|S0481: Ragnar Locker]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1489 - Service Stop|T1489: Service Stop]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Ragnar Locker](https://attack.mitre.org/software/S0481) has attempted to stop services associated with business applications and databases to release the lock on files used by these applications so they may be encrypted.(Citation: Sophos Ragnar May 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9212f940-021e-49b1-b500-fa1dd76b7132`.
