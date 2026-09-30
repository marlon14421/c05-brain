---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0085"
target_object: "T1204.002"
stix_relationship_id: "relationship--59b6b000-c8c5-4b4a-8801-5102de111111"
---
# Relationship 3383: G0085 — uses → T1204.002

**Source object:** [[01 ATT&CK/G0085 - FIN4|G0085: FIN4]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[FIN4](https://attack.mitre.org/groups/G0085) has lured victims to launch malicious attachments delivered via spearphishing emails (often sent from compromised accounts).(Citation: FireEye Hacking FIN4 Dec 2014)(Citation: FireEye Hacking FIN4 Video Dec 2014)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--59b6b000-c8c5-4b4a-8801-5102de111111`.
