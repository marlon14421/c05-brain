---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0124"
target_object: "T1016"
stix_relationship_id: "relationship--548e7315-5055-4434-96c1-1429779b0e2b"
---
# Relationship 4574: S0124 — uses → T1016

**Source object:** [[01 ATT&CK/S0124 - Pisloader|S0124: Pisloader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Pisloader](https://attack.mitre.org/software/S0124) has a command to collect the victim's IP address.(Citation: Palo Alto DNS Requests)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--548e7315-5055-4434-96c1-1429779b0e2b`.
