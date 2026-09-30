---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9022"
target_object: "T1555"
stix_relationship_id: "relationship--065810ad-cd56-401a-a19b-94dc302ed8e2"
---
# Relationship 3222: S9022 — uses → T1555

**Source object:** [[01 ATT&CK/S9022 - MirrorStealer|S9022: MirrorStealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1555 - Credentials from Password Stores|T1555: Credentials from Password Stores]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[MirrorStealer](https://attack.mitre.org/software/S9022) has the ability to steal credentials from email clients.(Citation: ESET MirrorFace DEC 2022)(Citation: Trend Micro Earth Kasha NOV 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--065810ad-cd56-401a-a19b-94dc302ed8e2`.
