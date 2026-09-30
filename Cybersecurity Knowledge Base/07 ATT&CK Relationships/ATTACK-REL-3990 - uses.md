---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1111"
target_object: "T1124"
stix_relationship_id: "relationship--b19ff9ec-1a64-4401-9bbd-e3af5a13ec7f"
---
# Relationship 3990: S1111 — uses → T1124

**Source object:** [[01 ATT&CK/S1111 - DarkGate|S1111: DarkGate]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1124 - System Time Discovery|T1124: System Time Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[DarkGate](https://attack.mitre.org/software/S1111) creates a log file for capturing keylogging, clipboard, and related data using the victim host's current date for the filename.(Citation: Ensilo Darkgate 2018) [DarkGate](https://attack.mitre.org/software/S1111) queries victim system epoch time during execution.(Citation: Ensilo Darkgate 2018) [DarkGate](https://attack.mitre.org/software/S1111) captures system time information as part of automated profiling on initial installation.(Citation: Trellix Darkgate 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b19ff9ec-1a64-4401-9bbd-e3af5a13ec7f`.
