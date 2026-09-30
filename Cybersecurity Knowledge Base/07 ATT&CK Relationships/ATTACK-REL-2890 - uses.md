---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0006"
target_object: "T1140"
stix_relationship_id: "relationship--f813e8ab-96d7-4880-a3c2-50e164d4bd66"
---
# Relationship 2890: C0006 — uses → T1140

**Source object:** [[01 ATT&CK/C0006 - Operation Honeybee|C0006: Operation Honeybee]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [Operation Honeybee](https://attack.mitre.org/campaigns/C0006), malicious files were decoded prior to execution.(Citation: McAfee Honeybee)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f813e8ab-96d7-4880-a3c2-50e164d4bd66`.
