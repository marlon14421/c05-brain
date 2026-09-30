---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0242"
target_object: "T1497.001"
stix_relationship_id: "relationship--36b27959-d265-4fb6-b33b-3a1e74d43206"
---
# Relationship 4605: S0242 — uses → T1497.001

**Source object:** [[01 ATT&CK/S0242 - SynAck|S0242: SynAck]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497.001 - System Checks|T1497.001: System Checks]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SynAck](https://attack.mitre.org/software/S0242) checks its directory location in an attempt to avoid launching in a sandbox.(Citation: SecureList SynAck Doppelgänging May 2018)(Citation: Kaspersky Lab SynAck May 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--36b27959-d265-4fb6-b33b-3a1e74d43206`.
