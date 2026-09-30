---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0203"
target_object: "T1048"
stix_relationship_id: "relationship--c5a0e330-ec5a-49cc-95b8-b7a5c49bd500"
---
# Relationship 6726: S0203 — uses → T1048

**Source object:** [[01 ATT&CK/S0203 - Hydraq|S0203: Hydraq]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1048 - Exfiltration Over Alternative Protocol|T1048: Exfiltration Over Alternative Protocol]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Hydraq](https://attack.mitre.org/software/S0203) connects to a predefined domain on port 443 to exfil gathered information.(Citation: Symantec Hydraq Jan 2010)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c5a0e330-ec5a-49cc-95b8-b7a5c49bd500`.
