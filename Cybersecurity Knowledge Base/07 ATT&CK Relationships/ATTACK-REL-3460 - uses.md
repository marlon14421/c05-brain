---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0094"
target_object: "T1016"
stix_relationship_id: "relationship--c1ea9582-0477-4226-a0ba-af03255d01dd"
---
# Relationship 3460: S0094 — uses → T1016

**Source object:** [[01 ATT&CK/S0094 - Trojan.Karagany|S0094: Trojan.Karagany]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Trojan.Karagany](https://attack.mitre.org/software/S0094) can gather information on the network configuration of a compromised host.(Citation: Secureworks Karagany July 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c1ea9582-0477-4226-a0ba-af03255d01dd`.
