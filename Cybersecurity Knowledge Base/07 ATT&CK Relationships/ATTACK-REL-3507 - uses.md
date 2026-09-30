---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0056"
target_object: "T1003.001"
stix_relationship_id: "relationship--a8e6ca7b-5d75-429a-b8f8-de97d5c277b3"
---
# Relationship 3507: S0056 — uses → T1003.001

**Source object:** [[01 ATT&CK/S0056 - Net Crawler|S0056: Net Crawler]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1003.001 - LSASS Memory|T1003.001: LSASS Memory]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Net Crawler](https://attack.mitre.org/software/S0056) uses credential dumpers such as [Mimikatz](https://attack.mitre.org/software/S0002) and [Windows Credential Editor](https://attack.mitre.org/software/S0005) to extract cached credentials from Windows systems.(Citation: Cylance Cleaver)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a8e6ca7b-5d75-429a-b8f8-de97d5c277b3`.
