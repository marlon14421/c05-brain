---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0335"
target_object: "T1049"
stix_relationship_id: "relationship--344f58f9-fefa-4c50-888c-25b2ef9e7dd2"
---
# Relationship 9246: S0335 — uses → T1049

**Source object:** [[01 ATT&CK/S0335 - Carbon|S0335: Carbon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1049 - System Network Connections Discovery|T1049: System Network Connections Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Carbon](https://attack.mitre.org/software/S0335) uses the netstat -r and netstat -an commands.(Citation: GovCERT Carbon May 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--344f58f9-fefa-4c50-888c-25b2ef9e7dd2`.
