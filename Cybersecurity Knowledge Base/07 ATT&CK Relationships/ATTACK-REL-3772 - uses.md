---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0282"
target_object: "T1056.001"
stix_relationship_id: "relationship--e6884060-8245-46ff-b71f-025c6a82eb3f"
---
# Relationship 3772: S0282 — uses → T1056.001

**Source object:** [[01 ATT&CK/S0282 - MacSpy|S0282: MacSpy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.001 - Keylogging|T1056.001: Keylogging]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[MacSpy](https://attack.mitre.org/software/S0282) captures keystrokes.(Citation: objsee mac malware 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e6884060-8245-46ff-b71f-025c6a82eb3f`.
