---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1085"
target_object: "T1680"
stix_relationship_id: "relationship--937b70c1-3024-4a39-95b0-5f76b8671a66"
---
# Relationship 2876: S1085 — uses → T1680

**Source object:** [[01 ATT&CK/S1085 - Sardonic|S1085: Sardonic]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1680 - Local Storage Discovery|T1680: Local Storage Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Sardonic](https://attack.mitre.org/software/S1085) has the ability to collect the C:\ drive serial number from a compromised machine.(Citation: Bitdefender Sardonic Aug 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--937b70c1-3024-4a39-95b0-5f76b8671a66`.
