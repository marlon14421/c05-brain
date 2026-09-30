---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0067"
target_object: "T1552.001"
stix_relationship_id: "relationship--a6e4853a-78a6-4c88-a7c5-58793d3e4dcd"
---
# Relationship 9626: S0067 — uses → T1552.001

**Source object:** [[01 ATT&CK/S0067 - pngdowner|S0067: pngdowner]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1552.001 - Credentials In Files|T1552.001: Credentials In Files]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

If an initial connectivity check fails, [pngdowner](https://attack.mitre.org/software/S0067) attempts to extract proxy details and credentials from Windows Protected Storage and from the IE Credentials Store. This allows the adversary to use the proxy credentials for subsequent requests if they enable outbound HTTP access.(Citation: CrowdStrike Putter Panda)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a6e4853a-78a6-4c88-a7c5-58793d3e4dcd`.
