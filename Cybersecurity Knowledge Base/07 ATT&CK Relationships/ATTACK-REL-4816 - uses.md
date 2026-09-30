---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0363"
target_object: "T1020"
stix_relationship_id: "relationship--45608b9a-ddd8-45f9-9152-bed384a1c8c3"
---
# Relationship 4816: S0363 — uses → T1020

**Source object:** [[01 ATT&CK/S0363 - Empire|S0363: Empire]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1020 - Automated Exfiltration|T1020: Automated Exfiltration]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Empire](https://attack.mitre.org/software/S0363) has the ability to automatically send collected data back to the threat actors' C2.(Citation: Talos Frankenstein June 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--45608b9a-ddd8-45f9-9152-bed384a1c8c3`.
