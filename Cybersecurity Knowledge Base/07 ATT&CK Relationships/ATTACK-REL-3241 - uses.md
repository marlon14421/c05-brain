---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0363"
target_object: "T1574.004"
stix_relationship_id: "relationship--c17d90b5-569c-42db-9265-ac99cad32093"
---
# Relationship 3241: S0363 — uses → T1574.004

**Source object:** [[01 ATT&CK/S0363 - Empire|S0363: Empire]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1574.004 - Dylib Hijacking|T1574.004: Dylib Hijacking]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Empire](https://attack.mitre.org/software/S0363) has a dylib hijacker module that generates a malicious dylib given the path to a legitimate dylib of a vulnerable application.(Citation: Github PowerShell Empire)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c17d90b5-569c-42db-9265-ac99cad32093`.
