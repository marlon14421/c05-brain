---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0096"
target_object: "T1574.001"
stix_relationship_id: "relationship--ffacfdd1-702e-4bb9-b60c-8e5c4cdf2a06"
---
# Relationship 3415: G0096 — uses → T1574.001

**Source object:** [[01 ATT&CK/G0096 - APT41|G0096: APT41]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1574.001 - DLL|T1574.001: DLL]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[APT41](https://attack.mitre.org/groups/G0096) has used search order hijacking to execute malicious payloads, such as [Winnti for Windows](https://attack.mitre.org/software/S0141).(Citation: Crowdstrike GTR2020 Mar 2020) [APT41](https://attack.mitre.org/groups/G0096) has also used legitimate executables to perform DLL side-loading of their malware.(Citation: FireEye APT41 Aug 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ffacfdd1-702e-4bb9-b60c-8e5c4cdf2a06`.
