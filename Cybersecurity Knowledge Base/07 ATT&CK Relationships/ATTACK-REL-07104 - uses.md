---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0236"
target_object: "T1016"
stix_relationship_id: "relationship--cfa38151-4972-4355-8071-dd36cb1be880"
---
# Relationship 7104: S0236 — uses → T1016

**Source object:** [[01 ATT&CK/S0236 - Kwampirs|S0236: Kwampirs]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kwampirs](https://attack.mitre.org/software/S0236) collects network adapter and interface information by using the commands ipconfig /all , arp -a and route print . It also collects the system's MAC address with getmac and domain configuration with net config workstation .(Citation: Symantec Orangeworm April 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cfa38151-4972-4355-8071-dd36cb1be880`.
