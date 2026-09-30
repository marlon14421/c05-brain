---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0581"
target_object: "T1053.005"
stix_relationship_id: "relationship--8fb40ded-3a84-48ad-ab52-342cf2ab629e"
---
# Relationship 8808: S0581 — uses → T1053.005

**Source object:** [[01 ATT&CK/S0581 - IronNetInjector|S0581: IronNetInjector]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.005 - Scheduled Task|T1053.005: Scheduled Task]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[IronNetInjector](https://attack.mitre.org/software/S0581) has used a task XML file named mssch.xml to run an IronPython script when a user logs in or when specific system events are created.(Citation: Unit 42 IronNetInjector February 2021 )

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8fb40ded-3a84-48ad-ab52-342cf2ab629e`.
