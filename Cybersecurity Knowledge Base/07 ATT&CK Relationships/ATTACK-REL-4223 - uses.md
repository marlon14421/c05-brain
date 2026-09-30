---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0345"
target_object: "T1547.001"
stix_relationship_id: "relationship--b228cc3b-a428-42e4-b6f3-994fe790e329"
---
# Relationship 4223: S0345 — uses → T1547.001

**Source object:** [[01 ATT&CK/S0345 - Seasalt|S0345: Seasalt]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Seasalt](https://attack.mitre.org/software/S0345) creates a Registry entry to ensure infection after reboot under HKLM\Software\Microsoft\Windows\currentVersion\Run .(Citation: McAfee Oceansalt Oct 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b228cc3b-a428-42e4-b6f3-994fe790e329`.
