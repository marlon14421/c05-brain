---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0088"
target_object: "T1059.003"
stix_relationship_id: "relationship--305ecc72-e820-44cb-ab52-593ccca814ff"
---
# Relationship 3729: S0088 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0088 - Kasidet|S0088: Kasidet]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Kasidet](https://attack.mitre.org/software/S0088) can execute commands using cmd.exe.(Citation: Zscaler Kasidet)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--305ecc72-e820-44cb-ab52-593ccca814ff`.
