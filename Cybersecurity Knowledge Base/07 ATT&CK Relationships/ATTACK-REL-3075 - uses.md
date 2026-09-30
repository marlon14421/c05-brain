---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0576"
target_object: "T1588.003"
stix_relationship_id: "relationship--443ee76b-8fd4-4485-bdbb-4a562f348be0"
---
# Relationship 3075: S0576 — uses → T1588.003

**Source object:** [[01 ATT&CK/S0576 - MegaCortex|S0576: MegaCortex]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1588.003 - Code Signing Certificates|T1588.003: Code Signing Certificates]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[MegaCortex](https://attack.mitre.org/software/S0576) has used code signing certificates issued to fake companies to bypass security controls.(Citation: IBM MegaCortex)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--443ee76b-8fd4-4485-bdbb-4a562f348be0`.
