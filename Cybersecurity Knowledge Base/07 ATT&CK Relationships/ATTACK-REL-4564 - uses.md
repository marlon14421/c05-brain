---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0271"
target_object: "T1680"
stix_relationship_id: "relationship--9e3f33db-5076-403b-b71e-71d898389e0b"
---
# Relationship 4564: S0271 — uses → T1680

**Source object:** [[01 ATT&CK/S0271 - KEYMARBLE|S0271: KEYMARBLE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1680 - Local Storage Discovery|T1680: Local Storage Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[KEYMARBLE](https://attack.mitre.org/software/S0271) has the capability to collect information on disk devices.(Citation: US-CERT KEYMARBLE Aug 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9e3f33db-5076-403b-b71e-71d898389e0b`.
