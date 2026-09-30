---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0587"
target_object: "T1059.004"
stix_relationship_id: "relationship--228c84a6-e6fa-45f3-9f89-36a0c95fb1e7"
---
# Relationship 4393: S0587 — uses → T1059.004

**Source object:** [[01 ATT&CK/S0587 - Penquin|S0587: Penquin]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.004 - Unix Shell|T1059.004: Unix Shell]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Penquin](https://attack.mitre.org/software/S0587) can execute remote commands using bash scripts.(Citation: Leonardo Turla Penquin May 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--228c84a6-e6fa-45f3-9f89-36a0c95fb1e7`.
