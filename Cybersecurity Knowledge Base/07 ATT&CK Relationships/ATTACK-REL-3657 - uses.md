---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0035"
target_object: "T1221"
stix_relationship_id: "relationship--26c62507-1a2b-4235-b80c-d5f7f52d1c95"
---
# Relationship 3657: G0035 — uses → T1221

**Source object:** [[01 ATT&CK/G0035 - Dragonfly|G0035: Dragonfly]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1221 - Template Injection|T1221: Template Injection]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Dragonfly](https://attack.mitre.org/groups/G0035) has injected SMB URLs into malicious Word spearphishing attachments to initiate [Forced Authentication](https://attack.mitre.org/techniques/T1187).(Citation: US-CERT TA18-074A)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--26c62507-1a2b-4235-b80c-d5f7f52d1c95`.
