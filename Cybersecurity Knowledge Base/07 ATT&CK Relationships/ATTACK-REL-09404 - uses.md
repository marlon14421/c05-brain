---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0189"
target_object: "T1055.012"
stix_relationship_id: "relationship--b1df64c9-782d-4452-8c4a-5ef933503c13"
---
# Relationship 9404: S0189 — uses → T1055.012

**Source object:** [[01 ATT&CK/S0189 - ISMInjector|S0189: ISMInjector]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.012 - Process Hollowing|T1055.012: Process Hollowing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ISMInjector](https://attack.mitre.org/software/S0189) hollows out a newly created process RegASM.exe and injects its payload into the hollowed process.(Citation: OilRig New Delivery Oct 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b1df64c9-782d-4452-8c4a-5ef933503c13`.
