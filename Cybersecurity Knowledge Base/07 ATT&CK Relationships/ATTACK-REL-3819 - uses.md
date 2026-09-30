---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1124"
target_object: "T1016"
stix_relationship_id: "relationship--faf41333-e316-45ea-8f52-faa98b4683d5"
---
# Relationship 3819: S1124 — uses → T1016

**Source object:** [[01 ATT&CK/S1124 - SocGholish|S1124: SocGholish]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SocGholish](https://attack.mitre.org/software/S1124) has the ability to enumerate the domain name of a victim, as well as if the host is a member of an Active Directory domain.(Citation: SocGholish-update)(Citation: Red Canary SocGholish March 2024)(Citation: Secureworks Gold Prelude Profile)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--faf41333-e316-45ea-8f52-faa98b4683d5`.
