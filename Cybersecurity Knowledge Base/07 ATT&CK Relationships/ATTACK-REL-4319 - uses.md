---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1111"
target_object: "T1680"
stix_relationship_id: "relationship--350b8d90-f1ab-4bdf-a47e-8413751ed56c"
---
# Relationship 4319: S1111 — uses → T1680

**Source object:** [[01 ATT&CK/S1111 - DarkGate|S1111: DarkGate]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1680 - Local Storage Discovery|T1680: Local Storage Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[DarkGate](https://attack.mitre.org/software/S1111) uses the Delphi methods Sysutils::DiskSize and GlobalMemoryStatusEx to collect disk size and physical memory as part of the malware's anti-analysis checks for running in a virtualized environment.(Citation: Ensilo Darkgate 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--350b8d90-f1ab-4bdf-a47e-8413751ed56c`.
