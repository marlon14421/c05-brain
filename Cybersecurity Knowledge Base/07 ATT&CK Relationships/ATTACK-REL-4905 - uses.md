---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1057"
target_object: "T1083"
stix_relationship_id: "relationship--69d75d5b-0780-4618-aca4-3a9c9b1e2aee"
---
# Relationship 4905: G1057 — uses → T1083

**Source object:** [[01 ATT&CK/G1057 - ShinyHunters|G1057: ShinyHunters]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ShinyHunters](https://attack.mitre.org/groups/G1057) has checked mount points for Oracle PeopleSoft configurations and has checked the process scheduler configuration file psappsrv.cfg. Additionally, [ShinyHunters](https://attack.mitre.org/groups/G1057) has read WebLogic server XML configurations files (config.xml).(Citation: Google_SHOracle_Jun2026)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--69d75d5b-0780-4618-aca4-3a9c9b1e2aee`.
