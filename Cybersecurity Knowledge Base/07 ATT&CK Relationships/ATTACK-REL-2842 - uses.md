---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0348"
target_object: "T1012"
stix_relationship_id: "relationship--8875e27f-9f8d-418b-8937-a2c4d1858607"
---
# Relationship 2842: S0348 — uses → T1012

**Source object:** [[01 ATT&CK/S0348 - Cardinal RAT|S0348: Cardinal RAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1012 - Query Registry|T1012: Query Registry]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Cardinal RAT](https://attack.mitre.org/software/S0348) contains watchdog functionality that periodically ensures HKCU\Software\Microsoft\Windows NT\CurrentVersion\Windows\Load is set to point to its executable.(Citation: PaloAlto CardinalRat Apr 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8875e27f-9f8d-418b-8937-a2c4d1858607`.
