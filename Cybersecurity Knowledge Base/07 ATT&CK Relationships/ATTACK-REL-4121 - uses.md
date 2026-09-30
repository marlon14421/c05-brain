---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0334"
target_object: "T1686.003"
stix_relationship_id: "relationship--0bdf79b8-64d2-4403-b14a-4000c5867e05"
---
# Relationship 4121: S0334 — uses → T1686.003

**Source object:** [[01 ATT&CK/S0334 - DarkComet|S0334: DarkComet]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1686.003 - Windows Host Firewall|T1686.003: Windows Host Firewall]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[DarkComet](https://attack.mitre.org/software/S0334) can disable Security Center functions like the Windows Firewall.(Citation: TrendMicro DarkComet Sept 2014)(Citation: Malwarebytes DarkComet March 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0bdf79b8-64d2-4403-b14a-4000c5867e05`.
