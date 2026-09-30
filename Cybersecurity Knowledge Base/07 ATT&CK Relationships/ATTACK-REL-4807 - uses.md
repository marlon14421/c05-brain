---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0049"
target_object: "T1140"
stix_relationship_id: "relationship--67469b79-67e2-4932-9776-b09a82871723"
---
# Relationship 4807: G0049 — uses → T1140

**Source object:** [[01 ATT&CK/G0049 - OilRig|G0049: OilRig]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

A [OilRig](https://attack.mitre.org/groups/G0049) macro has run a PowerShell command to decode file contents. [OilRig](https://attack.mitre.org/groups/G0049) has also used [certutil](https://attack.mitre.org/software/S0160) to decode base64-encoded files on victims.(Citation: FireEye APT34 Dec 2017)(Citation: OilRig New Delivery Oct 2017)(Citation: Unit 42 OopsIE! Feb 2018)(Citation: Crowdstrike GTR2020 Mar 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--67469b79-67e2-4932-9776-b09a82871723`.
