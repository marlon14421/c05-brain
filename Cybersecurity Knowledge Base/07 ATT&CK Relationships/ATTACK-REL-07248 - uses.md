---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0581"
target_object: "T1057"
stix_relationship_id: "relationship--10b4ef89-5f69-4809-a410-37256407b5fa"
---
# Relationship 7248: S0581 — uses → T1057

**Source object:** [[01 ATT&CK/S0581 - IronNetInjector|S0581: IronNetInjector]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[IronNetInjector](https://attack.mitre.org/software/S0581) can identify processes via C# methods such as GetProcessesByName and running [Tasklist](https://attack.mitre.org/software/S0057) with the Python os.popen function.(Citation: Unit 42 IronNetInjector February 2021 )

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--10b4ef89-5f69-4809-a410-37256407b5fa`.
