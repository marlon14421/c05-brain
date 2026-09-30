---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0114"
target_object: "T1036.005"
stix_relationship_id: "relationship--74cc85f8-594d-428b-a44a-5ede87df0ad9"
---
# Relationship 4299: G0114 — uses → T1036.005

**Source object:** [[01 ATT&CK/G0114 - Chimera|G0114: Chimera]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Chimera](https://attack.mitre.org/groups/G0114) has renamed malware to GoogleUpdate.exe and WinRAR to jucheck.exe, RecordedTV.ms, teredo.tmp, update.exe, and msadcs1.exe.(Citation: Cycraft Chimera April 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--74cc85f8-594d-428b-a44a-5ede87df0ad9`.
