---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1104"
target_object: "T1027"
stix_relationship_id: "relationship--f35fa774-0344-4678-b104-a0dd1003197a"
---
# Relationship 9480: S1104 — uses → T1027

**Source object:** [[01 ATT&CK/S1104 - SLOWPULSE|S1104: SLOWPULSE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SLOWPULSE](https://attack.mitre.org/software/S1104) can hide malicious code in the padding regions between legitimate functions in the Pulse Secure `libdsplibs.so` file.(Citation: Mandiant Pulse Secure Zero-Day April 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f35fa774-0344-4678-b104-a0dd1003197a`.
