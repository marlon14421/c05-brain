---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9010"
target_object: "T1105"
stix_relationship_id: "relationship--d8613097-6ef1-4b84-8641-0951cab8376f"
---
# Relationship 5419: S9010 — uses → T1105

**Source object:** [[01 ATT&CK/S9010 - GlassWorm|S9010: GlassWorm]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[GlassWorm](https://attack.mitre.org/software/S9010) has downloaded additional payloads from C2.(Citation: Koi Glassworm New Tricks December 2025)(Citation: Koi Glassworm Extensions November 2025)(Citation: Socket GlassWorm January 2026)(Citation: Koi GlassWorm Rust December 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d8613097-6ef1-4b84-8641-0951cab8376f`.
