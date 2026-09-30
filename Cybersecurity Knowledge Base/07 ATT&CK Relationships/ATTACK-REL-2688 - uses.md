---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0194"
target_object: "T1547.005"
stix_relationship_id: "relationship--be2d0ead-f24c-4b76-bdd9-695d163bcbf3"
---
# Relationship 2688: S0194 — uses → T1547.005

**Source object:** [[01 ATT&CK/S0194 - PowerSploit|S0194: PowerSploit]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.005 - Security Support Provider|T1547.005: Security Support Provider]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[PowerSploit](https://attack.mitre.org/software/S0194)'s Install-SSP Persistence module can be used to establish by installing a SSP DLL.(Citation: GitHub PowerSploit May 2012)(Citation: PowerSploit Documentation)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--be2d0ead-f24c-4b76-bdd9-695d163bcbf3`.
