---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0363"
target_object: "T1083"
stix_relationship_id: "relationship--75cc19f5-00b4-43e2-8eae-f633693dbe56"
---
# Relationship 8918: S0363 — uses → T1083

**Source object:** [[01 ATT&CK/S0363 - Empire|S0363: Empire]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Empire](https://attack.mitre.org/software/S0363) includes various modules for finding files of interest on hosts and network shares.(Citation: Github PowerShell Empire)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--75cc19f5-00b4-43e2-8eae-f633693dbe56`.
