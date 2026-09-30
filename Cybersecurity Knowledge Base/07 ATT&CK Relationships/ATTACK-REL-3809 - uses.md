---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0060"
target_object: "T1033"
stix_relationship_id: "relationship--fea6e347-95f5-4d97-8781-4cc15d6b5b0c"
---
# Relationship 3809: S0060 — uses → T1033

**Source object:** [[01 ATT&CK/S0060 - Sys10|S0060: Sys10]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Sys10](https://attack.mitre.org/software/S0060) collects the account name of the logged-in user and sends it to the C2.(Citation: Baumgartner Naikon 2015)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fea6e347-95f5-4d97-8781-4cc15d6b5b0c`.
