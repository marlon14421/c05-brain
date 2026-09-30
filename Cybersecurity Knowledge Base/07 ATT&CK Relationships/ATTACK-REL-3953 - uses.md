---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1124"
target_object: "T1048.003"
stix_relationship_id: "relationship--e3b20c80-7b6e-4a0a-8e69-f2d948cadd0e"
---
# Relationship 3953: S1124 — uses → T1048.003

**Source object:** [[01 ATT&CK/S1124 - SocGholish|S1124: SocGholish]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1048.003 - Exfiltration Over Unencrypted Non-C2 Protocol|T1048.003: Exfiltration Over Unencrypted Non-C2 Protocol]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SocGholish](https://attack.mitre.org/software/S1124) can exfiltrate data directly to its C2 domain via HTTP.(Citation: Red Canary SocGholish March 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e3b20c80-7b6e-4a0a-8e69-f2d948cadd0e`.
