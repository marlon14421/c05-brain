---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1066"
target_object: "T1204.002"
stix_relationship_id: "relationship--80219528-7b8e-415a-b2f2-c3678bccc185"
---
# Relationship 4591: S1066 — uses → T1204.002

**Source object:** [[01 ATT&CK/S1066 - DarkTortilla|S1066: DarkTortilla]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[DarkTortilla](https://attack.mitre.org/software/S1066) has relied on a user to open a malicious document or archived file delivered via email for initial execution.(Citation: Secureworks DarkTortilla Aug 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--80219528-7b8e-415a-b2f2-c3678bccc185`.
