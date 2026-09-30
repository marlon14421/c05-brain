---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0347"
target_object: "T1543.003"
stix_relationship_id: "relationship--e6d80908-fa46-46b5-aee3-30d2e54edec0"
---
# Relationship 2956: S0347 — uses → T1543.003

**Source object:** [[01 ATT&CK/S0347 - AuditCred|S0347: AuditCred]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1543.003 - Windows Service|T1543.003: Windows Service]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[AuditCred](https://attack.mitre.org/software/S0347) is installed as a new service on the system.(Citation: TrendMicro Lazarus Nov 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e6d80908-fa46-46b5-aee3-30d2e54edec0`.
