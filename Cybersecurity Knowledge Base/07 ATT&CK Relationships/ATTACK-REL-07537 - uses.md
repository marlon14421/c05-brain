---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9034"
target_object: "T1218.007"
stix_relationship_id: "relationship--d868ae80-0dcb-420c-ad6e-e0974f26fea1"
---
# Relationship 7537: S9034 — uses → T1218.007

**Source object:** [[01 ATT&CK/S9034 - Tsundere Botnet|S9034: Tsundere Botnet]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.007 - Msiexec|T1218.007: Msiexec]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Tsundere Botnet](https://attack.mitre.org/software/S9034) has been distributed via an MSI installer.(Citation: SecureListUbiedo_Tsundere_Nov2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d868ae80-0dcb-420c-ad6e-e0974f26fea1`.
