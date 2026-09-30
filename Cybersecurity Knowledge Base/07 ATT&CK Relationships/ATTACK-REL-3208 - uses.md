---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1056"
target_object: "T1546.016"
stix_relationship_id: "relationship--69cdaa38-6957-4917-81d6-44c382820c1d"
---
# Relationship 3208: G1056 — uses → T1546.016

**Source object:** [[01 ATT&CK/G1056 - TeamPCP|G1056: TeamPCP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1546.016 - Installer Packages|T1546.016: Installer Packages]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[TeamPCP](https://attack.mitre.org/groups/G1056) has modified software packages with preinstall scripts to download and execute malicious payloads.(Citation: Wiz Mini Shai-Hulud MAY 2026)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--69cdaa38-6957-4917-81d6-44c382820c1d`.
