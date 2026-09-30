---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0129"
target_object: "T1218.004"
stix_relationship_id: "relationship--42440c0c-f28b-4c42-94af-dc4cad6a8dd7"
---
# Relationship 4212: G0129 — uses → T1218.004

**Source object:** [[01 ATT&CK/G0129 - Mustang Panda|G0129: Mustang Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.004 - InstallUtil|T1218.004: InstallUtil]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Mustang Panda](https://attack.mitre.org/groups/G0129) has used InstallUtil.exe to execute a malicious Beacon stager.(Citation: Anomali MUSTANG PANDA October 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--42440c0c-f28b-4c42-94af-dc4cad6a8dd7`.
