---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0033"
target_object: "T1010"
stix_relationship_id: "relationship--10c6cc56-a028-4c2a-b24e-38d97fb4ebb7"
---
# Relationship 4676: S0033 — uses → T1010

**Source object:** [[01 ATT&CK/S0033 - NetTraveler|S0033: NetTraveler]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1010 - Application Window Discovery|T1010: Application Window Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[NetTraveler](https://attack.mitre.org/software/S0033) reports window names along with keylogger information to provide application context.(Citation: Kaspersky NetTraveler)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--10c6cc56-a028-4c2a-b24e-38d97fb4ebb7`.
