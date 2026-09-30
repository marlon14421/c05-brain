---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0013"
target_object: "T1140"
stix_relationship_id: "relationship--cb67b57d-2ab3-4971-9b8d-83768df36df0"
---
# Relationship 5233: S0013 — uses → T1140

**Source object:** [[01 ATT&CK/S0013 - PlugX|S0013: PlugX]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PlugX](https://attack.mitre.org/software/S0013) decompresses and decrypts itself using the Microsoft API call RtlDecompressBuffer.(Citation: CIRCL PlugX March 2013)(Citation: Trend Micro DRBControl February 2020)(Citation: Proofpoint TA416 Europe March 2022) [PlugX](https://attack.mitre.org/software/S0013) has also decrypted its payloads in memory.(Citation: Eset PlugX Korplug Mustang Panda March 2022)(Citation: Cisco Talos MUSTANG PANDA PLUGX PUBLOAD MAY 2022)(Citation: EclecticIQ Mustang Panda PlugX)(Citation: Sophos Mustang Panda PLUGX)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cb67b57d-2ab3-4971-9b8d-83768df36df0`.
