---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1111"
target_object: "T1036.007"
stix_relationship_id: "relationship--45ca99b5-7d7b-4067-9108-a9847e4123d6"
---
# Relationship 5225: S1111 — uses → T1036.007

**Source object:** [[01 ATT&CK/S1111 - DarkGate|S1111: DarkGate]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.007 - Double File Extension|T1036.007: Double File Extension]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DarkGate](https://attack.mitre.org/software/S1111) masquerades malicious LNK files as PDF objects using the double extension .pdf.lnk .(Citation: Trellix Darkgate 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--45ca99b5-7d7b-4067-9108-a9847e4123d6`.
