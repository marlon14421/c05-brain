---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0256"
target_object: "T1059.003"
stix_relationship_id: "relationship--c5535462-7d2c-4a97-a717-b29ea23e00cd"
---
# Relationship 7925: S0256 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0256 - Mosquito|S0256: Mosquito]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mosquito](https://attack.mitre.org/software/S0256) executes cmd.exe and uses a pipe to read the results and send back the output to the C2 server.(Citation: ESET Turla Mosquito Jan 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c5535462-7d2c-4a97-a717-b29ea23e00cd`.
