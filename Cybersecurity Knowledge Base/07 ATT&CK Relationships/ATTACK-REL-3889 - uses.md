---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0063"
target_object: "T1584.008"
stix_relationship_id: "relationship--72601af4-90e2-4dcc-8bb1-6f9dc6db8205"
---
# Relationship 3889: C0063 — uses → T1584.008

**Source object:** [[01 ATT&CK/C0063 - 2025 Poland Wiper Attacks|C0063: 2025 Poland Wiper Attacks]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1584.008 - Network Devices|T1584.008: Network Devices]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During the [2025 Poland Wiper Attacks](https://attack.mitre.org/campaigns/C0063), the adversaries used compromised Cisco routers for network communications.(Citation: CERT Polska)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--72601af4-90e2-4dcc-8bb1-6f9dc6db8205`.
