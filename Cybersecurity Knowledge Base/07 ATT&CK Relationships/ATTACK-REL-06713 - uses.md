---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0150"
target_object: "T1105"
stix_relationship_id: "relationship--be31bf6d-ce4f-4620-8940-445f35ff90a7"
---
# Relationship 6713: S0150 — uses → T1105

**Source object:** [[01 ATT&CK/S0150 - POSHSPY|S0150: POSHSPY]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[POSHSPY](https://attack.mitre.org/software/S0150) downloads and executes additional PowerShell code and Windows binaries.(Citation: FireEye POSHSPY April 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--be31bf6d-ce4f-4620-8940-445f35ff90a7`.
