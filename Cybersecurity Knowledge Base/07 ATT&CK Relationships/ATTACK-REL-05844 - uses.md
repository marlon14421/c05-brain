---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0092"
target_object: "T1016"
stix_relationship_id: "relationship--dc187ed1-3987-4575-b1af-dc150e4329f8"
---
# Relationship 5844: S0092 — uses → T1016

**Source object:** [[01 ATT&CK/S0092 - Agent.btz|S0092: Agent.btz]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Agent.btz](https://attack.mitre.org/software/S0092) collects the network adapter’s IP and MAC address as well as IP addresses of the network adapter’s default gateway, primary/secondary WINS, DHCP, and DNS servers, and saves them into a log file.(Citation: ThreatExpert Agent.btz)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dc187ed1-3987-4575-b1af-dc150e4329f8`.
