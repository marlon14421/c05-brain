---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0698"
target_object: "T1218.010"
stix_relationship_id: "relationship--b2b37e14-5dbc-4faa-955a-7172b242e828"
---
# Relationship 3892: S0698 — uses → T1218.010

**Source object:** [[01 ATT&CK/S0698 - HermeticWizard|S0698: HermeticWizard]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.010 - Regsvr32|T1218.010: Regsvr32]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[HermeticWizard](https://attack.mitre.org/software/S0698) has used `regsvr32.exe /s /i` to execute malicious payloads.(Citation: ESET Hermetic Wizard March 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b2b37e14-5dbc-4faa-955a-7172b242e828`.
