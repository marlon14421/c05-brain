---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0613"
target_object: "T1140"
stix_relationship_id: "relationship--bf9adcbf-3d35-4d70-b681-e7180f3c08da"
---
# Relationship 6478: S0613 — uses → T1140

**Source object:** [[01 ATT&CK/S0613 - PS1|S0613: PS1]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PS1](https://attack.mitre.org/software/S0613) can use an XOR key to decrypt a PowerShell loader and payload binary.(Citation: BlackBerry CostaRicto November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bf9adcbf-3d35-4d70-b681-e7180f3c08da`.
