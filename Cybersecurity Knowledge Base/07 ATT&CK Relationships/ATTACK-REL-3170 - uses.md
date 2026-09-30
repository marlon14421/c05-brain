---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0011"
target_object: "T1588.002"
stix_relationship_id: "relationship--86169d65-b154-402d-918c-4b4602d71cd0"
---
# Relationship 3170: G0011 — uses → T1588.002

**Source object:** [[01 ATT&CK/G0011 - PittyTiger|G0011: PittyTiger]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1588.002 - Tool|T1588.002: Tool]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[PittyTiger](https://attack.mitre.org/groups/G0011) has obtained and used tools such as [Mimikatz](https://attack.mitre.org/software/S0002) and [gsecdump](https://attack.mitre.org/software/S0008).(Citation: Bizeul 2014)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--86169d65-b154-402d-918c-4b4602d71cd0`.
