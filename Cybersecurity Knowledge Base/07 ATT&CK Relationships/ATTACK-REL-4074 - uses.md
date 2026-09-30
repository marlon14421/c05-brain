---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9018"
target_object: "T1055.012"
stix_relationship_id: "relationship--33786d33-6b8e-4668-bc63-352152214685"
---
# Relationship 4074: S9018 — uses → T1055.012

**Source object:** [[01 ATT&CK/S9018 - HeartCrypt|S9018: HeartCrypt]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.012 - Process Hollowing|T1055.012: Process Hollowing]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

For .NET payloads, [HeartCrypt](https://attack.mitre.org/software/S9018) can use process hollowing to inject into processes spawned by csc.exe or AppLaunch.exe.(Citation: Palo Alto HeartCrypt DEC 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--33786d33-6b8e-4668-bc63-352152214685`.
