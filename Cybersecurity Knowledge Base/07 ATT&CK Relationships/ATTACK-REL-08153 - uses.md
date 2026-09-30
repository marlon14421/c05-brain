---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0007"
target_object: "T1584.008"
stix_relationship_id: "relationship--22708534-eb0e-4217-93a9-74615c537411"
---
# Relationship 8153: G0007 — uses → T1584.008

**Source object:** [[01 ATT&CK/G0007 - APT28|G0007: APT28]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1584.008 - Network Devices|T1584.008: Network Devices]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT28](https://attack.mitre.org/groups/G0007) compromised Ubiquiti network devices to act as collection devices for credentials compromised via phishing webpages.(Citation: Leonard TAG 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--22708534-eb0e-4217-93a9-74615c537411`.
