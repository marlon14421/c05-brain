---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1035"
target_object: "T1071.001"
stix_relationship_id: "relationship--226403d7-7318-4f15-9cf6-83fd6684c33f"
---
# Relationship 3301: G1035 — uses → T1071.001

**Source object:** [[01 ATT&CK/G1035 - Winter Vivern|G1035: Winter Vivern]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Winter Vivern](https://attack.mitre.org/groups/G1035) uses HTTP and HTTPS protocols for exfiltration and command and control activity.(Citation: SentinelOne WinterVivern 2023)(Citation: CERT-UA WinterVivern 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--226403d7-7318-4f15-9cf6-83fd6684c33f`.
