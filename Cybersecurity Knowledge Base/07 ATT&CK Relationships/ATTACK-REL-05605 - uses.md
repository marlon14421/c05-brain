---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1149"
target_object: "T1102"
stix_relationship_id: "relationship--c313b2dd-2f30-408d-aeef-59e41ef38927"
---
# Relationship 5605: S1149 — uses → T1102

**Source object:** [[01 ATT&CK/S1149 - CHIMNEYSWEEP|S1149: CHIMNEYSWEEP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1102 - Web Service|T1102: Web Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CHIMNEYSWEEP](https://attack.mitre.org/software/S1149) has the ability to use use Telegram channels to return a list of commands to be executed, to download additional payloads, or to create a reverse shell.(Citation: Mandiant ROADSWEEP August 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c313b2dd-2f30-408d-aeef-59e41ef38927`.
