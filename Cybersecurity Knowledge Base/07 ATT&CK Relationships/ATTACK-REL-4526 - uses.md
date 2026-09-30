---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0119"
target_object: "T1489"
stix_relationship_id: "relationship--e2763cbf-c068-47b5-a871-3b20a368497f"
---
# Relationship 4526: G0119 — uses → T1489

**Source object:** [[01 ATT&CK/G0119 - Indrik Spider|G0119: Indrik Spider]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1489 - Service Stop|T1489: Service Stop]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Indrik Spider](https://attack.mitre.org/groups/G0119) has used [PsExec](https://attack.mitre.org/software/S0029) to stop services prior to the execution of ransomware.(Citation: Symantec WastedLocker June 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e2763cbf-c068-47b5-a871-3b20a368497f`.
