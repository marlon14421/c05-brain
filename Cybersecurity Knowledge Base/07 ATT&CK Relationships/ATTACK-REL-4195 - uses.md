---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0665"
target_object: "T1204.002"
stix_relationship_id: "relationship--3da23733-c783-4743-8238-5fc96714409b"
---
# Relationship 4195: S0665 — uses → T1204.002

**Source object:** [[01 ATT&CK/S0665 - ThreatNeedle|S0665: ThreatNeedle]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ThreatNeedle](https://attack.mitre.org/software/S0665) relies on a victim to click on a malicious document for initial execution.(Citation: Kaspersky ThreatNeedle Feb 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3da23733-c783-4743-8238-5fc96714409b`.
