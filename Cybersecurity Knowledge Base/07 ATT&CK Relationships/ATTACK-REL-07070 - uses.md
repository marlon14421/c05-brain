---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0554"
target_object: "T1484.001"
stix_relationship_id: "relationship--e50d74be-2705-4937-9bd9-7b0913901e27"
---
# Relationship 7070: S0554 — uses → T1484.001

**Source object:** [[01 ATT&CK/S0554 - Egregor|S0554: Egregor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1484.001 - Group Policy Modification|T1484.001: Group Policy Modification]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Egregor](https://attack.mitre.org/software/S0554) can modify the GPO to evade detection.(Citation: Cybereason Egregor Nov 2020) (Citation: Intrinsec Egregor Nov 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e50d74be-2705-4937-9bd9-7b0913901e27`.
