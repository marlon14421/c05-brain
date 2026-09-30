---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1185"
target_object: "T1518"
stix_relationship_id: "relationship--bad8e857-fe92-49d3-8bd7-50a6665c0902"
---
# Relationship 4193: S1185 — uses → T1518

**Source object:** [[01 ATT&CK/S1185 - LightSpy|S1185: LightSpy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1518 - Software Discovery|T1518: Software Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

If sent the command `16001`, [LightSpy](https://attack.mitre.org/software/S1185) uses the `NSFileManger contentsOfDirectoryAtPath()` to enumerate the Applications folder to collect the bundle name, bundle identifier, and version information from each application's `info.plist` file. The results are then converted into a JSON blob for exfiltration.(Citation: Huntress LightSpy macOS 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bad8e857-fe92-49d3-8bd7-50a6665c0902`.
