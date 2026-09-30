---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0451"
target_object: "T1569.001"
stix_relationship_id: "relationship--131d75f1-84c3-4ef8-b858-7f74aa7ce157"
---
# Relationship 2704: S0451 — uses → T1569.001

**Source object:** [[01 ATT&CK/S0451 - LoudMiner|S0451: LoudMiner]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1569.001 - Launchctl|T1569.001: Launchctl]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[LoudMiner](https://attack.mitre.org/software/S0451) launched the QEMU services in the /Library/LaunchDaemons/ folder using launchctl . It also uses launchctl to unload all [Launch Daemon](https://attack.mitre.org/techniques/T1543/004)s when updating to a newer version of [LoudMiner](https://attack.mitre.org/software/S0451).(Citation: ESET LoudMiner June 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--131d75f1-84c3-4ef8-b858-7f74aa7ce157`.
