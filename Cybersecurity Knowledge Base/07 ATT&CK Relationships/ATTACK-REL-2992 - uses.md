---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0236"
target_object: "T1007"
stix_relationship_id: "relationship--36f0915e-66aa-4062-b909-35414c639ae1"
---
# Relationship 2992: S0236 — uses → T1007

**Source object:** [[01 ATT&CK/S0236 - Kwampirs|S0236: Kwampirs]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1007 - System Service Discovery|T1007: System Service Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Kwampirs](https://attack.mitre.org/software/S0236) collects a list of running services with the command tasklist /svc .(Citation: Symantec Orangeworm April 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--36f0915e-66aa-4062-b909-35414c639ae1`.
