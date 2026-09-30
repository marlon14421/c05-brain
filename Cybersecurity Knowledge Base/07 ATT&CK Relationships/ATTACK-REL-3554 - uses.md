---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0090"
target_object: "T1566.002"
stix_relationship_id: "relationship--a7492314-41f3-4785-afee-8869f16d0204"
---
# Relationship 3554: G0090 — uses → T1566.002

**Source object:** [[01 ATT&CK/G0090 - WIRTE|G0090: WIRTE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.002 - Spearphishing Link|T1566.002: Spearphishing Link]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[WIRTE](https://attack.mitre.org/groups/G0090) has sent targeted spearphishing emails with malicious links directing victims to malware downloads.(Citation: Check Point Wirte NOV 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a7492314-41f3-4785-afee-8869f16d0204`.
