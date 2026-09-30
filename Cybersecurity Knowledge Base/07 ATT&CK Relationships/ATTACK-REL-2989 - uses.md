---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1018"
target_object: "T1055.012"
stix_relationship_id: "relationship--b58eb56c-9992-4fcd-ae4f-b7a1301667f0"
---
# Relationship 2989: S1018 — uses → T1055.012

**Source object:** [[01 ATT&CK/S1018 - Saint Bot|S1018: Saint Bot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.012 - Process Hollowing|T1055.012: Process Hollowing]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

The [Saint Bot](https://attack.mitre.org/software/S1018) loader has used API calls to spawn `MSBuild.exe` in a suspended state before injecting the decrypted [Saint Bot](https://attack.mitre.org/software/S1018) binary into it.(Citation: Palo Alto Unit 42 OutSteel SaintBot February 2022 )

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b58eb56c-9992-4fcd-ae4f-b7a1301667f0`.
