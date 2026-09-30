---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0331"
target_object: "T1033"
stix_relationship_id: "relationship--3e370a6e-2a3c-4e56-aa57-fecab8d09709"
---
# Relationship 5383: S0331 — uses → T1033

**Source object:** [[01 ATT&CK/S0331 - Agent Tesla|S0331: Agent Tesla]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Agent Tesla](https://attack.mitre.org/software/S0331) can collect the username from the victim’s machine.(Citation: DigiTrust Agent Tesla Jan 2017)(Citation: Fortinet Agent Tesla April 2018)(Citation: Malwarebytes Agent Tesla April 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3e370a6e-2a3c-4e56-aa57-fecab8d09709`.
