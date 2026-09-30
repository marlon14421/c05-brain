---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0532"
target_object: "T1012"
stix_relationship_id: "relationship--f8c754dd-a4a8-4507-bce2-c738e5354a3c"
---
# Relationship 4666: S0532 — uses → T1012

**Source object:** [[01 ATT&CK/S0532 - Lucifer|S0532: Lucifer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1012 - Query Registry|T1012: Query Registry]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Lucifer](https://attack.mitre.org/software/S0532) can check for existing stratum cryptomining information in HKLM\Software\Microsoft\Windows\CurrentVersion\spreadCpuXmr – %stratum info% .(Citation: Unit 42 Lucifer June 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f8c754dd-a4a8-4507-bce2-c738e5354a3c`.
