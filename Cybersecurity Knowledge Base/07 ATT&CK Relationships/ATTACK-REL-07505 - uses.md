---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0443"
target_object: "T1140"
stix_relationship_id: "relationship--97323d60-9623-4b3e-8ff9-50370fef4e5b"
---
# Relationship 7505: S0443 — uses → T1140

**Source object:** [[01 ATT&CK/S0443 - MESSAGETAP|S0443: MESSAGETAP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

After checking for the existence of two files, keyword_parm.txt and parm.txt, [MESSAGETAP](https://attack.mitre.org/software/S0443) XOR decodes and read the contents of the files. (Citation: FireEye MESSAGETAP October 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--97323d60-9623-4b3e-8ff9-50370fef4e5b`.
