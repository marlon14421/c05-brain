---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0553"
target_object: "T1518.001"
stix_relationship_id: "relationship--ed08418e-2143-4633-bfc9-cac436adde2b"
---
# Relationship 2760: S0553 — uses → T1518.001

**Source object:** [[01 ATT&CK/S0553 - MoleNet|S0553: MoleNet]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1518.001 - Security Software Discovery|T1518.001: Security Software Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[MoleNet](https://attack.mitre.org/software/S0553) can use WMI commands to check the system for firewall and antivirus software.(Citation: Cybereason Molerats Dec 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ed08418e-2143-4633-bfc9-cac436adde2b`.
