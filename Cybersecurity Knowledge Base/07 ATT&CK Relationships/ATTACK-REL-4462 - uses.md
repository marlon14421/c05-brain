---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0030"
target_object: "T1012"
stix_relationship_id: "relationship--3a217a5a-b6c4-47c5-822a-5b278385c811"
---
# Relationship 4462: S0030 — uses → T1012

**Source object:** [[01 ATT&CK/S0030 - Carbanak|S0030: Carbanak]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1012 - Query Registry|T1012: Query Registry]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Carbanak](https://attack.mitre.org/software/S0030) checks the Registry key HKCU\Software\Microsoft\Windows\CurrentVersion\Internet Settings for proxy configurations information.(Citation: FireEye CARBANAK June 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3a217a5a-b6c4-47c5-822a-5b278385c811`.
