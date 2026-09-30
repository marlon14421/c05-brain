---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0661"
target_object: "T1041"
stix_relationship_id: "relationship--2c93a27a-c6f0-46b9-857b-b746e2204670"
---
# Relationship 4113: S0661 — uses → T1041

**Source object:** [[01 ATT&CK/S0661 - FoggyWeb|S0661: FoggyWeb]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[FoggyWeb](https://attack.mitre.org/software/S0661) can remotely exfiltrate sensitive information from a compromised AD FS server.(Citation: MSTIC FoggyWeb September 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2c93a27a-c6f0-46b9-857b-b746e2204670`.
