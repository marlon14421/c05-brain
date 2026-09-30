---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1130"
target_object: "T1218.007"
stix_relationship_id: "relationship--dda729e3-eb8c-4c4d-a2cf-b34c5f9f8c52"
---
# Relationship 3615: S1130 — uses → T1218.007

**Source object:** [[01 ATT&CK/S1130 - Raspberry Robin|S1130: Raspberry Robin]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.007 - Msiexec|T1218.007: Msiexec]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Raspberry Robin](https://attack.mitre.org/software/S1130) uses msiexec.exe for post-installation communication to command and control infrastructure.(Citation: RedCanary RaspberryRobin 2022) Msiexec.exe is executed referencing a remote resource for second-stage payload retrieval and execution.(Citation: TrendMicro RaspberryRobin 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dda729e3-eb8c-4c4d-a2cf-b34c5f9f8c52`.
