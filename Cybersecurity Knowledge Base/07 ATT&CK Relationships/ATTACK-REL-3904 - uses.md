---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1060"
target_object: "T1016"
stix_relationship_id: "relationship--9c057a7e-c815-4d43-a250-6696dc3691e2"
---
# Relationship 3904: S1060 — uses → T1016

**Source object:** [[01 ATT&CK/S1060 - Mafalda|S1060: Mafalda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Mafalda](https://attack.mitre.org/software/S1060) can use the `GetAdaptersInfo` function to retrieve information about network adapters and the `GetIpNetTable` function to retrieve the IPv4 to physical network address mapping table.(Citation: SentinelLabs Metador Sept 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9c057a7e-c815-4d43-a250-6696dc3691e2`.
