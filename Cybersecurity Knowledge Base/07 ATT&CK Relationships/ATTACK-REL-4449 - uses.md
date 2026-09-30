---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1001"
target_object: "S0100"
stix_relationship_id: "relationship--bed01612-b213-44dc-aabc-19ea87ef28b8"
---
# Relationship 4449: G1001 — uses → S0100

**Source object:** [[01 ATT&CK/G1001 - HEXANE|G1001: HEXANE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0100 - ipconfig|S0100: ipconfig]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: ClearSky Siamesekitten August 2021)(Citation: Zscaler Lyceum DnsSystem June 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bed01612-b213-44dc-aabc-19ea87ef28b8`.
