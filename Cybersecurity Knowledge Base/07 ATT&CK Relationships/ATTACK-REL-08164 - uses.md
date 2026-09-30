---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0141"
target_object: "T1057"
stix_relationship_id: "relationship--563e67ee-9cc8-4f44-9d3a-3611e19a1a3c"
---
# Relationship 8164: S0141 — uses → T1057

**Source object:** [[01 ATT&CK/S0141 - Winnti for Windows|S0141: Winnti for Windows]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Winnti for Windows](https://attack.mitre.org/software/S0141) can check if the explorer.exe process is responsible for calling its install function.(Citation: Novetta Winnti April 2015)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--563e67ee-9cc8-4f44-9d3a-3611e19a1a3c`.
