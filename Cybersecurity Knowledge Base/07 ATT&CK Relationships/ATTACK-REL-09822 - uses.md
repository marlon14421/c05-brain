---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0028"
target_object: "T1040"
stix_relationship_id: "relationship--899c49f0-4a1b-44d8-81e6-fd927a252bd6"
---
# Relationship 9822: C0028 — uses → T1040

**Source object:** [[01 ATT&CK/C0028 - 2015 Ukraine Electric Power Attack|C0028: 2015 Ukraine Electric Power Attack]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1040 - Network Sniffing|T1040: Network Sniffing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During the [2015 Ukraine Electric Power Attack](https://attack.mitre.org/campaigns/C0028), [Sandworm Team](https://attack.mitre.org/groups/G0034) used [BlackEnergy](https://attack.mitre.org/software/S0089)’s network sniffer module to discover user credentials being sent over the network between the local LAN and the power grid’s industrial control systems. (Citation: Charles McLellan March 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--899c49f0-4a1b-44d8-81e6-fd927a252bd6`.
