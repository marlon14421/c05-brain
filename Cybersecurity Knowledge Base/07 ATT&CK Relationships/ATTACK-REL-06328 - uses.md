---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0053"
target_object: "S0005"
stix_relationship_id: "relationship--432f40d2-5309-4cc1-9544-2943233c3c2c"
---
# Relationship 6328: G0053 — uses → S0005

**Source object:** [[01 ATT&CK/G0053 - FIN5|G0053: FIN5]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0005 - Windows Credential Editor|S0005: Windows Credential Editor]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: DarkReading FireEye FIN5 Oct 2015)(Citation: Mandiant FIN5 GrrCON Oct 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--432f40d2-5309-4cc1-9544-2943233c3c2c`.
