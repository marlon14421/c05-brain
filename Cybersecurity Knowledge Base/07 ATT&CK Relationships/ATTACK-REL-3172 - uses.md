---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0608"
target_object: "T1027"
stix_relationship_id: "relationship--b9de1f4c-1978-4efe-9bd0-f525b6acaeb1"
---
# Relationship 3172: S0608 — uses → T1027

**Source object:** [[01 ATT&CK/S0608 - Conficker|S0608: Conficker]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Conficker](https://attack.mitre.org/software/S0608) has obfuscated its code to prevent its removal from host machines.(Citation: Trend Micro Conficker)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b9de1f4c-1978-4efe-9bd0-f525b6acaeb1`.
