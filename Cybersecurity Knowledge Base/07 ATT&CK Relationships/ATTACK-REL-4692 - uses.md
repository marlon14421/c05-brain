---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1247"
target_object: "T1490"
stix_relationship_id: "relationship--76fbcff9-f756-47d7-8a86-8bb8dc748433"
---
# Relationship 4692: S1247 — uses → T1490

**Source object:** [[01 ATT&CK/S1247 - Embargo|S1247: Embargo]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1490 - Inhibit System Recovery|T1490: Inhibit System Recovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Embargo](https://attack.mitre.org/software/S1247) has cleared files from the recycle bin by invoking `SHEmptyRecycleBinW()` and disabled Windows recovery through `C:\Windows\System32\cmd.exe /q /c bcdedit /set {default} recoveryenabled no`.(Citation: Cyble Embargo Ransomware May 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--76fbcff9-f756-47d7-8a86-8bb8dc748433`.
