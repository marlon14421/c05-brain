---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1001"
target_object: "T1059.001"
stix_relationship_id: "relationship--9e0a0a20-e78f-491b-b828-934525bf160b"
---
# Relationship 2716: G1001 — uses → T1059.001

**Source object:** [[01 ATT&CK/G1001 - HEXANE|G1001: HEXANE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[HEXANE](https://attack.mitre.org/groups/G1001) has used PowerShell-based tools and scripts for discovery and collection on compromised hosts.(Citation: SecureWorks August 2019)(Citation: Kaspersky APT Trends Q1 April 2021)(Citation: Kaspersky Lyceum October 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9e0a0a20-e78f-491b-b828-934525bf160b`.
