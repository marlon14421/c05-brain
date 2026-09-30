---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0267"
target_object: "T1059.003"
stix_relationship_id: "relationship--e73efb12-ee40-4896-8df6-c0c8b6cb0c92"
---
# Relationship 2747: S0267 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0267 - FELIXROOT|S0267: FELIXROOT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[FELIXROOT](https://attack.mitre.org/software/S0267) executes batch scripts on the victim’s machine, and can launch a reverse shell for command execution.(Citation: FireEye FELIXROOT July 2018)(Citation: ESET GreyEnergy Oct 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e73efb12-ee40-4896-8df6-c0c8b6cb0c92`.
