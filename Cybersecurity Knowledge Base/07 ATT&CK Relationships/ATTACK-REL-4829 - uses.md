---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0148"
target_object: "T1119"
stix_relationship_id: "relationship--a83182d2-b619-4ca4-984b-21ecfe43da26"
---
# Relationship 4829: S0148 — uses → T1119

**Source object:** [[01 ATT&CK/S0148 - RTM|S0148: RTM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1119 - Automated Collection|T1119: Automated Collection]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[RTM](https://attack.mitre.org/software/S0148) monitors browsing activity and automatically captures screenshots if a victim browses to a URL matching one of a list of strings.(Citation: ESET RTM Feb 2017)(Citation: Unit42 Redaman January 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a83182d2-b619-4ca4-984b-21ecfe43da26`.
