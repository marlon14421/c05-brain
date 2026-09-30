---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0333"
target_object: "T1497.001"
stix_relationship_id: "relationship--750c8d62-74f3-4566-95fc-97f1685c9ca0"
---
# Relationship 4092: S0333 — uses → T1497.001

**Source object:** [[01 ATT&CK/S0333 - UBoatRAT|S0333: UBoatRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497.001 - System Checks|T1497.001: System Checks]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[UBoatRAT](https://attack.mitre.org/software/S0333) checks for virtualization software such as VMWare, VirtualBox, or QEmu on the compromised machine.(Citation: PaloAlto UBoatRAT Nov 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--750c8d62-74f3-4566-95fc-97f1685c9ca0`.
