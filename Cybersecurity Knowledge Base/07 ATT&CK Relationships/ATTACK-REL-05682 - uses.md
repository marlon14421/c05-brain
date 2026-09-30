---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0598"
target_object: "T1140"
stix_relationship_id: "relationship--0686ee2f-ff46-418b-b6e8-1766e4dc33a8"
---
# Relationship 5682: S0598 — uses → T1140

**Source object:** [[01 ATT&CK/S0598 - P.A.S. Webshell|S0598: P.A.S. Webshell]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[P.A.S. Webshell](https://attack.mitre.org/software/S0598) can use a decryption mechanism to process a user supplied password and allow execution.(Citation: ANSSI Sandworm January 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0686ee2f-ff46-418b-b6e8-1766e4dc33a8`.
