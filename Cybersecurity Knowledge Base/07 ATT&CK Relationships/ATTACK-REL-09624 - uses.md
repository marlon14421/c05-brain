---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0379"
target_object: "T1202"
stix_relationship_id: "relationship--b5612c39-e246-409b-97cb-57067cfa27b4"
---
# Relationship 9624: S0379 — uses → T1202

**Source object:** [[01 ATT&CK/S0379 - Revenge RAT|S0379: Revenge RAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1202 - Indirect Command Execution|T1202: Indirect Command Execution]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Revenge RAT](https://attack.mitre.org/software/S0379) uses the [Forfiles](https://attack.mitre.org/software/S0193) utility to execute commands on the system.(Citation: Cofense RevengeRAT Feb 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b5612c39-e246-409b-97cb-57067cfa27b4`.
