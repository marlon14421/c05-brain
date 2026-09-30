---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0018"
target_object: "T1082"
stix_relationship_id: "relationship--eb85fa2e-3c50-4130-9717-8688237fecbc"
---
# Relationship 6865: G0018 — uses → T1082

**Source object:** [[01 ATT&CK/G0018 - admin@338|G0018: admin@338]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[admin@338](https://attack.mitre.org/groups/G0018) actors used the following commands after exploiting a machine with [LOWBALL](https://attack.mitre.org/software/S0042) malware to obtain information about the OS: ver >> %temp%\download systeminfo >> %temp%\download (Citation: FireEye admin@338)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--eb85fa2e-3c50-4130-9717-8688237fecbc`.
