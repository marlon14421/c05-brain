---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0059"
target_object: "T1567"
stix_relationship_id: "relationship--043ea873-396a-4ba8-a3e3-1f9af11c986e"
---
# Relationship 2797: G0059 — uses → T1567

**Source object:** [[01 ATT&CK/G0059 - Magic Hound|G0059: Magic Hound]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1567 - Exfiltration Over Web Service|T1567: Exfiltration Over Web Service]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Magic Hound](https://attack.mitre.org/groups/G0059) has used the Telegram API `sendMessage` to relay data on compromised devices.(Citation: Google Iran Threats October 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--043ea873-396a-4ba8-a3e3-1f9af11c986e`.
