---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0005"
target_object: "T1003.001"
stix_relationship_id: "relationship--935971d6-0af2-4683-971a-9acb523733fe"
---
# Relationship 3781: S0005 — uses → T1003.001

**Source object:** [[01 ATT&CK/S0005 - Windows Credential Editor|S0005: Windows Credential Editor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1003.001 - LSASS Memory|T1003.001: LSASS Memory]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Windows Credential Editor](https://attack.mitre.org/software/S0005) can dump credentials.(Citation: Amplia WCE)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--935971d6-0af2-4683-971a-9acb523733fe`.
