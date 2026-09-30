---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1109"
target_object: "T1083"
stix_relationship_id: "relationship--dee2ef91-fe07-423a-8ad3-551c99b7a112"
---
# Relationship 3501: S1109 — uses → T1083

**Source object:** [[01 ATT&CK/S1109 - PACEMAKER|S1109: PACEMAKER]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[PACEMAKER](https://attack.mitre.org/software/S1109) can parse `/proc/"process_name"/cmdline` to look for the string `dswsd` within the command line.(Citation: Mandiant Pulse Secure Zero-Day April 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dee2ef91-fe07-423a-8ad3-551c99b7a112`.
