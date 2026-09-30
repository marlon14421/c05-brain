---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0044"
target_object: "T1068"
stix_relationship_id: "relationship--976202db-cdfa-4c4e-bc09-9b3cad90e6fb"
---
# Relationship 2818: S0044 — uses → T1068

**Source object:** [[01 ATT&CK/S0044 - JHUHUGIT|S0044: JHUHUGIT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1068 - Exploitation for Privilege Escalation|T1068: Exploitation for Privilege Escalation]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[JHUHUGIT](https://attack.mitre.org/software/S0044) has exploited CVE-2015-1701 and CVE-2015-2387 to escalate privileges.(Citation: ESET Sednit Part 1)(Citation: ESET Sednit July 2015)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--976202db-cdfa-4c4e-bc09-9b3cad90e6fb`.
