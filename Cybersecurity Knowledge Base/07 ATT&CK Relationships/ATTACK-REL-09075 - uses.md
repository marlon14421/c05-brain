---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9010"
target_object: "T1059.007"
stix_relationship_id: "relationship--a7c7be1a-68a4-408b-94c8-3bbebeed618d"
---
# Relationship 9075: S9010 — uses → T1059.007

**Source object:** [[01 ATT&CK/S9010 - GlassWorm|S9010: GlassWorm]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.007 - JavaScript|T1059.007: JavaScript]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[GlassWorm](https://attack.mitre.org/software/S9010) has leveraged JavaScript to execute its malicious code to include its hidden Unicode characters using the `eval` call.(Citation: Koi Glassworm Extensions November 2025)(Citation: Koi Glassworm InvisibleCode October 2025)(Citation: Aikido GlassWorm October 2025)(Citation: Socket GlassWorm January 2026) [GlassWorm](https://attack.mitre.org/software/S9010) has also utilized encrypted payloads compiled in JavaScript.(Citation: Koi Glassworm New Tricks December 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a7c7be1a-68a4-408b-94c8-3bbebeed618d`.
