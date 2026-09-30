---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0439"
target_object: "T1059.003"
stix_relationship_id: "relationship--1e5cae4c-240d-495b-9eca-34bba583d894"
---
# Relationship 3162: S0439 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0439 - Okrum|S0439: Okrum]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Okrum](https://attack.mitre.org/software/S0439)'s backdoor has used cmd.exe to execute arbitrary commands as well as batch scripts to update itself to a newer version.(Citation: ESET Okrum July 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1e5cae4c-240d-495b-9eca-34bba583d894`.
