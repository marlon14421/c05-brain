---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0126"
target_object: "T1140"
stix_relationship_id: "relationship--ad8fdfa4-5e0b-437d-9723-9bc5a272f465"
---
# Relationship 9670: S0126 — uses → T1140

**Source object:** [[01 ATT&CK/S0126 - ComRAT|S0126: ComRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ComRAT](https://attack.mitre.org/software/S0126) has used unique per machine passwords to decrypt the orchestrator payload and a hardcoded XOR key to decrypt its communications module. [ComRAT](https://attack.mitre.org/software/S0126) has also used a unique password to decrypt the file used for its hidden file system.(Citation: ESET ComRAT May 2020)(Citation: CISA ComRAT Oct 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ad8fdfa4-5e0b-437d-9723-9bc5a272f465`.
