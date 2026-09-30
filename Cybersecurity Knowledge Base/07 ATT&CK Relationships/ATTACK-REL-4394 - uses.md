---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0266"
target_object: "T1041"
stix_relationship_id: "relationship--3ed5a1c3-e7c8-4fb7-bfcf-401b29f5f47c"
---
# Relationship 4394: S0266 — uses → T1041

**Source object:** [[01 ATT&CK/S0266 - TrickBot|S0266: TrickBot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[TrickBot](https://attack.mitre.org/software/S0266) can send information about the compromised host and upload data to a hardcoded C2 server.(Citation: Cyberreason Anchor December 2019)(Citation: Bitdefender Trickbot VNC module Whitepaper 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3ed5a1c3-e7c8-4fb7-bfcf-401b29f5f47c`.
