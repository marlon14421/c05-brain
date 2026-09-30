---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0240"
target_object: "T1567.002"
stix_relationship_id: "relationship--d7d9a45b-0f61-43a0-93fd-7924c9307f72"
---
# Relationship 4655: S0240 — uses → T1567.002

**Source object:** [[01 ATT&CK/S0240 - ROKRAT|S0240: ROKRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1567.002 - Exfiltration to Cloud Storage|T1567.002: Exfiltration to Cloud Storage]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ROKRAT](https://attack.mitre.org/software/S0240) can send collected data to cloud storage services such as PCloud.(Citation: Malwarebytes RokRAT VBA January 2021)(Citation: Volexity InkySquid RokRAT August 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d7d9a45b-0f61-43a0-93fd-7924c9307f72`.
