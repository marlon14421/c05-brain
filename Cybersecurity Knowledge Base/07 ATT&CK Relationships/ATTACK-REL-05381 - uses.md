---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0067"
target_object: "T1106"
stix_relationship_id: "relationship--82c9b9a1-5fbe-49e5-8685-12a03a66ef8d"
---
# Relationship 5381: G0067 — uses → T1106

**Source object:** [[01 ATT&CK/G0067 - APT37|G0067: APT37]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT37](https://attack.mitre.org/groups/G0067) leverages the Windows API calls: VirtualAlloc(), WriteProcessMemory(), and CreateRemoteThread() for process injection.(Citation: Talos Group123)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--82c9b9a1-5fbe-49e5-8685-12a03a66ef8d`.
