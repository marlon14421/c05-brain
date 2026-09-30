---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1035"
target_object: "T1059.001"
stix_relationship_id: "relationship--f31ff00d-794c-41ef-ab92-65bf7ff25169"
---
# Relationship 8583: G1035 — uses → T1059.001

**Source object:** [[01 ATT&CK/G1035 - Winter Vivern|G1035: Winter Vivern]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Winter Vivern](https://attack.mitre.org/groups/G1035) passed execution from document macros to PowerShell scripts during initial access operations.(Citation: DomainTools WinterVivern 2021) [Winter Vivern](https://attack.mitre.org/groups/G1035) used batch scripts that called PowerShell commands as part of initial access and installation operations.(Citation: CERT-UA WinterVivern 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f31ff00d-794c-41ef-ab92-65bf7ff25169`.
