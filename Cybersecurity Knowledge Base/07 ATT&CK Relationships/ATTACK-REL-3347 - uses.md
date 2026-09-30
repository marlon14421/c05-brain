---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0024"
target_object: "T1587.001"
stix_relationship_id: "relationship--6ce6e5d1-a9e1-43bb-a296-e6bd188081f4"
---
# Relationship 3347: C0024 — uses → T1587.001

**Source object:** [[01 ATT&CK/C0024 - SolarWinds Compromise|C0024: SolarWinds Compromise]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1587.001 - Malware|T1587.001: Malware]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

For the [SolarWinds Compromise](https://attack.mitre.org/campaigns/C0024), [APT29](https://attack.mitre.org/groups/G0016) used numerous pieces of malware that were likely developed for or by the group, including [SUNBURST](https://attack.mitre.org/software/S0559), [SUNSPOT](https://attack.mitre.org/software/S0562), [Raindrop](https://attack.mitre.org/software/S0565), and [TEARDROP](https://attack.mitre.org/software/S0560).(Citation: FireEye SUNBURST Backdoor December 2020)(Citation: CrowdStrike SUNSPOT Implant January 2021)(Citation: Microsoft Deep Dive Solorigate January 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6ce6e5d1-a9e1-43bb-a296-e6bd188081f4`.
