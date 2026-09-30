---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0006"
target_object: "T1083"
stix_relationship_id: "relationship--15fd646c-172b-4458-945a-69a07a5648bb"
---
# Relationship 4928: C0006 — uses → T1083

**Source object:** [[01 ATT&CK/C0006 - Operation Honeybee|C0006: Operation Honeybee]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [Operation Honeybee](https://attack.mitre.org/campaigns/C0006), the threat actors used a malicious DLL to search for files with specific keywords.(Citation: McAfee Honeybee)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--15fd646c-172b-4458-945a-69a07a5648bb`.
