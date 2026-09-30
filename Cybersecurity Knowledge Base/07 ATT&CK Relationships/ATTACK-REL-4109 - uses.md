---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1120"
target_object: "T1001.003"
stix_relationship_id: "relationship--1ad251b3-f49e-438d-98e0-3e310d683a8d"
---
# Relationship 4109: S1120 — uses → T1001.003

**Source object:** [[01 ATT&CK/S1120 - FRAMESTING|S1120: FRAMESTING]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1001.003 - Protocol or Service Impersonation|T1001.003: Protocol or Service Impersonation]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[FRAMESTING](https://attack.mitre.org/software/S1120) uses a cookie named `DSID` to mimic the name of a cookie used by Ivanti Connect Secure appliances for maintaining VPN sessions.(Citation: Mandiant Cutting Edge Part 2 January 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1ad251b3-f49e-438d-98e0-3e310d683a8d`.
