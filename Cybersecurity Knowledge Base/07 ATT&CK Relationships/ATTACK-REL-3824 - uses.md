---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0689"
target_object: "T1542.003"
stix_relationship_id: "relationship--03ecffe3-d09c-40f5-bbc8-ffa4acc4bdb4"
---
# Relationship 3824: S0689 — uses → T1542.003

**Source object:** [[01 ATT&CK/S0689 - WhisperGate|S0689: WhisperGate]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1542.003 - Bootkit|T1542.003: Bootkit]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[WhisperGate](https://attack.mitre.org/software/S0689) overwrites the MBR with a bootloader component that performs destructive wiping operations on hard drives and displays a fake ransom note when the host boots.(Citation: Crowdstrike WhisperGate January 2022)(Citation: Cybereason WhisperGate February 2022)(Citation: Microsoft WhisperGate January 2022)(Citation: Cisco Ukraine Wipers January 2022)(Citation: Medium S2W WhisperGate January 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--03ecffe3-d09c-40f5-bbc8-ffa4acc4bdb4`.
