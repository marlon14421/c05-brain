---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0039"
target_object: "T1095"
stix_relationship_id: "relationship--e8b7172d-ae96-4334-98f5-3bfc71122474"
---
# Relationship 7936: C0039 — uses → T1095

**Source object:** [[01 ATT&CK/C0039 - Versa Director Zero Day Exploitation|C0039: Versa Director Zero Day Exploitation]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1095 - Non-Application Layer Protocol|T1095: Non-Application Layer Protocol]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Versa Director Zero Day Exploitation](https://attack.mitre.org/campaigns/C0039) used a non-standard TCP session to initialize communication prior to establishing HTTPS command and control.(Citation: Lumen Versa 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e8b7172d-ae96-4334-98f5-3bfc71122474`.
