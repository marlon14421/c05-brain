---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0591"
target_object: "T1059.001"
stix_relationship_id: "relationship--8fba0fad-b83d-4252-b7ef-c4d1b3529cba"
---
# Relationship 4076: S0591 — uses → T1059.001

**Source object:** [[01 ATT&CK/S0591 - ConnectWise|S0591: ConnectWise]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ConnectWise](https://attack.mitre.org/software/S0591) can be used to execute PowerShell commands on target machines.(Citation: Anomali Static Kitten February 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8fba0fad-b83d-4252-b7ef-c4d1b3529cba`.
