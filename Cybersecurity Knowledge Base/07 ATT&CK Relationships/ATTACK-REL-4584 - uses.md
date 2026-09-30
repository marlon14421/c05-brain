---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0034"
target_object: "T1572"
stix_relationship_id: "relationship--6cde759a-8c53-4b6e-a110-09fd8ad3759f"
---
# Relationship 4584: C0034 — uses → T1572

**Source object:** [[01 ATT&CK/C0034 - 2022 Ukraine Electric Power Attack|C0034: 2022 Ukraine Electric Power Attack]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1572 - Protocol Tunneling|T1572: Protocol Tunneling]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During the [2022 Ukraine Electric Power Attack](https://attack.mitre.org/campaigns/C0034), [Sandworm Team](https://attack.mitre.org/groups/G0034) deployed the GOGETTER tunneler software to establish a “Yamux” TLS-based C2 channel with an external server(s).(Citation: Mandiant-Sandworm-Ukraine-2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6cde759a-8c53-4b6e-a110-09fd8ad3759f`.
