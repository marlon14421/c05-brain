---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0234"
target_object: "T1123"
stix_relationship_id: "relationship--1148c339-09f2-4518-9562-c6aa11d5474f"
---
# Relationship 3916: S0234 — uses → T1123

**Source object:** [[01 ATT&CK/S0234 - Bandook|S0234: Bandook]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1123 - Audio Capture|T1123: Audio Capture]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Bandook](https://attack.mitre.org/software/S0234) has modules that are capable of capturing audio.(Citation: EFF Manul Aug 2016)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1148c339-09f2-4518-9562-c6aa11d5474f`.
