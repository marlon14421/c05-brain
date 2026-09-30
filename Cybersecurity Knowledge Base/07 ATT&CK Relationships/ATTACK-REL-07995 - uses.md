---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0021"
target_object: "T1140"
stix_relationship_id: "relationship--a575b110-f622-4813-9fa7-bef6287bcb7b"
---
# Relationship 7995: C0021 — uses → T1140

**Source object:** [[01 ATT&CK/C0021 - C0021|C0021: C0021]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [C0021](https://attack.mitre.org/campaigns/C0021), the threat actors deobfuscated encoded PowerShell commands including use of the specific string `'FromBase'+0x40+'String'`, in place of `FromBase64String` which is normally used to decode base64.(Citation: FireEye APT29 Nov 2018)(Citation: Microsoft Unidentified Dec 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a575b110-f622-4813-9fa7-bef6287bcb7b`.
