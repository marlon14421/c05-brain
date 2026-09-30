---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0692"
target_object: "T1021.006"
stix_relationship_id: "relationship--db1f0baf-27ee-4e1c-9d8f-6a82918b5f0f"
---
# Relationship 8317: S0692 — uses → T1021.006

**Source object:** [[01 ATT&CK/S0692 - SILENTTRINITY|S0692: SILENTTRINITY]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1021.006 - Windows Remote Management|T1021.006: Windows Remote Management]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SILENTTRINITY](https://attack.mitre.org/software/S0692) tracks `TrustedHosts` and can move laterally to these targets via WinRM.(Citation: GitHub SILENTTRINITY Modules July 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--db1f0baf-27ee-4e1c-9d8f-6a82918b5f0f`.
