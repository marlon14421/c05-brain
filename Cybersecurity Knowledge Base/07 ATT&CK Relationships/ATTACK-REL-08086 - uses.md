---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0045"
target_object: "T1078"
stix_relationship_id: "relationship--44273d72-b0d9-42ee-9e8e-53d1b39f0651"
---
# Relationship 8086: G0045 — uses → T1078

**Source object:** [[01 ATT&CK/G0045 - menuPass|G0045: menuPass]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1078 - Valid Accounts|T1078: Valid Accounts]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[menuPass](https://attack.mitre.org/groups/G0045) has used valid accounts including shared between Managed Service Providers and clients to move between the two environments.(Citation: PWC Cloud Hopper April 2017)(Citation: Symantec Cicada November 2020)(Citation: District Court of NY APT10 Indictment December 2018)(Citation: Securelist APT10 March 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--44273d72-b0d9-42ee-9e8e-53d1b39f0651`.
