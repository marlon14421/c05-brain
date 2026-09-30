---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0012"
target_object: "T1547.006"
stix_relationship_id: "relationship--e6a1906d-43d1-454c-8150-053759421b74"
---
# Relationship 4153: C0012 — uses → T1547.006

**Source object:** [[01 ATT&CK/C0012 - Operation CuckooBees|C0012: Operation CuckooBees]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.006 - Kernel Modules and Extensions|T1547.006: Kernel Modules and Extensions]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [Operation CuckooBees](https://attack.mitre.org/campaigns/C0012), attackers used a signed kernel rootkit to establish additional persistence.(Citation: Cybereason OperationCuckooBees May 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e6a1906d-43d1-454c-8150-053759421b74`.
