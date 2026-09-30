---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0096"
target_object: "T1082"
stix_relationship_id: "relationship--c088f23e-b741-453c-a710-01990dead853"
---
# Relationship 2647: S0096 — uses → T1082

**Source object:** [[01 ATT&CK/S0096 - Systeminfo|S0096: Systeminfo]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Systeminfo](https://attack.mitre.org/software/S0096) can be used to gather information about the operating system.(Citation: TechNet Systeminfo)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c088f23e-b741-453c-a710-01990dead853`.
