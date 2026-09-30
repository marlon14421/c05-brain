---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0384"
target_object: "T1082"
stix_relationship_id: "relationship--9dfb9740-1641-4306-8ee8-38318be3ae42"
---
# Relationship 4211: S0384 — uses → T1082

**Source object:** [[01 ATT&CK/S0384 - Dridex|S0384: Dridex]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Dridex](https://attack.mitre.org/software/S0384) has collected the computer name and OS architecture information from the system.(Citation: Checkpoint Dridex Jan 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9dfb9740-1641-4306-8ee8-38318be3ae42`.
