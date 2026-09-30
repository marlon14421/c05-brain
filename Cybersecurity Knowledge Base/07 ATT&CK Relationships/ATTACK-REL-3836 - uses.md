---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0046"
target_object: "T1190"
stix_relationship_id: "relationship--198a9aa2-5d98-46c2-b43b-0191786049e7"
---
# Relationship 3836: G0046 — uses → T1190

**Source object:** [[01 ATT&CK/G0046 - FIN7|G0046: FIN7]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1190 - Exploit Public-Facing Application|T1190: Exploit Public-Facing Application]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[FIN7](https://attack.mitre.org/groups/G0046) has compromised targeted organizations through exploitation of CVE-2021-31207 in Exchange.(Citation: Microsoft Ransomware as a Service)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--198a9aa2-5d98-46c2-b43b-0191786049e7`.
