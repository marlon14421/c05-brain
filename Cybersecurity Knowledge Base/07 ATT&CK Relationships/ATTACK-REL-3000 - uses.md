---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1007"
target_object: "T1588.002"
stix_relationship_id: "relationship--a6ff725c-1c60-44dd-8f78-22f1b009bbb5"
---
# Relationship 3000: G1007 — uses → T1588.002

**Source object:** [[01 ATT&CK/G1007 - Aoqin Dragon|G1007: Aoqin Dragon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1588.002 - Tool|T1588.002: Tool]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Aoqin Dragon](https://attack.mitre.org/groups/G1007) obtained the Heyoka open source exfiltration tool and subsequently modified it for their operations.(Citation: SentinelOne Aoqin Dragon June 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a6ff725c-1c60-44dd-8f78-22f1b009bbb5`.
