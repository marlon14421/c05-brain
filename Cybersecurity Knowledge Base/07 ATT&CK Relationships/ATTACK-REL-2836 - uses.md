---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0046"
target_object: "T1686"
stix_relationship_id: "relationship--83ce1f0c-8afc-472d-af07-71b359d7781b"
---
# Relationship 2836: G0046 — uses → T1686

**Source object:** [[01 ATT&CK/G0046 - FIN7|G0046: FIN7]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1686 - Disable or Modify System Firewall|T1686: Disable or Modify System Firewall]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[FIN7](https://attack.mitre.org/groups/G0046) has added a firewall rule to allow TCP port 59999 inbound and a rule to allow sshd.exe on TCP port 9898.(Citation: BlackBerry_FIN7_April2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--83ce1f0c-8afc-472d-af07-71b359d7781b`.
