---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0205"
target_object: "T1016"
stix_relationship_id: "relationship--43c0d71b-d82e-45f0-89ce-acb94810c1c3"
---
# Relationship 3937: S0205 — uses → T1016

**Source object:** [[01 ATT&CK/S0205 - Naid|S0205: Naid]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Naid](https://attack.mitre.org/software/S0205) collects the domain name from a compromised host.(Citation: Symantec Naid June 2012)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--43c0d71b-d82e-45f0-89ce-acb94810c1c3`.
