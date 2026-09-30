---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1048"
target_object: "T1105"
stix_relationship_id: "relationship--0a8e3f80-f415-450c-9976-feb917facd8a"
---
# Relationship 9644: S1048 — uses → T1105

**Source object:** [[01 ATT&CK/S1048 - macOS.OSAMiner|S1048: macOS.OSAMiner]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[macOS.OSAMiner](https://attack.mitre.org/software/S1048) has used `curl` to download a [Stripped Payloads](https://attack.mitre.org/techniques/T1027/008) from a public facing adversary-controlled webpage.

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0a8e3f80-f415-450c-9976-feb917facd8a`.
